local FireServer
plr = game:GetService("Players").LocalPlayer
s = plr.PlayerGui.ScreenGui.ClientScript
repeat wait()
for i,v in pairs(getgc()) do
    if type(v) == "function" and getfenv(v).script == s and getinfo(v).name == "FireServer" then 
        FireServer = v
    end
end
until FireServer ~= nil
local eggs = {}
for i,v in pairs(workspace.Eggs:GetChildren()) do
    if not table.find(eggs,v.Name) then
        table.insert(eggs,v.Name)
    end
end
local af,as,ao,egg = false,false,false,""
local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/AikaV3rm/UiLib/master/Lib.lua')))()
local w = library:CreateWindow("Bubble gum simulator")
local b = w:CreateFolder("Tools")
b:Toggle("Auto Farm",function(bool)
    af = bool
end)
b:Toggle("Auto Sell",function(bool)
    as = bool
end)
b:Toggle("Auto Open Eggs",function(bool)
    ao = bool
end)
b:Dropdown("Eggs",eggs,true,function(a)
    egg = a
end)
b:Button("Unlock All Islands",function()
    hrp = plr.Character.HumanoidRootPart
    for i,v in pairs(workspace.FloatingIslands.Overworld:GetChildren()) do
        if v:FindFirstChild("RootPart") then
            hrp.Parent = nil
            hrp.CFrame = v.RootPart.CFrame*CFrame.new(0,10,0)
            hrp.Parent = game.Players.LocalPlayer.Character
            wait(.1)
        end
    end
end)
b:Button("Destroy Gui",function(value)
    for i,v in pairs(game:GetService("CoreGui"):GetChildren()) do
        if v:FindFirstChild("HiI'mSexyDon'tTouchMePls") then
            v:Destroy()
        end
    end
end)
spawn(function()
    while wait() do
        if af then
            FireServer(nil,"BlowBubble")
        end
    end
end)
spawn(function()
    while wait() do
        if ao then
            if workspace.Eggs:FindFirstChild(egg) and (workspace.Eggs[egg].Hotkey.Position - plr.Character.HumanoidRootPart.Position).Magnitude < 15 then
                FireServer(nil,"PurchaseEgg",egg,"Multi")
            end
        end
    end
end)
spawn(function()
    while wait() do
        pcall(function()
            if as then
                bubbles = plr.PlayerGui.ScreenGui.StatsFrame.Bubble.Amount
                bubbles = bubbles.Text:split("/")
                if bubbles[1] == bubbles[2] then
                    FireServer(nil,"Teleport","Sell")
                    wait(math.random(100,150)/150)
                end
            end
        end)
    end
end)

local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/NiceBBMBThai12/NBTScript/main/UI-Library-Robloxx"))()
local window = library:Win()
local tap1 = window:addtap("main")
local tap2 = window:addtap("-")
local page1 = tap1:addpage()
local page2 = tap1:addpage()
local page3 = tap1:addpage()
local page4 = tap1:addpage()
page1:Ti("autofarm NEXIz")

page1:Toggle("Auto farm",_false, function(value)
_G.farm = value
end)

spawn(function()
    while wait() do
        if _G.farm then
local A_1 = 
{
}
local Event = game:GetService("ReplicatedStorage").Assets.Events["attack with a weapon"]
Event:FireServer(A_1)

        end
    end
end)

page1:Toggle("Auto mon",_false, function(value)
_G.mon = value
end)

spawn(function()
    while wait() do
        if _G.mon then
local A_1 = 
{
}
local Event = game:GetService("ReplicatedStorage").Assets.Events["attack with a weapon"]
Event:FireServer(A_1)

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1243.64208984375, 577.5426025390625, -507.5172424316406)

        end
    end
end)

page1:Toggle("Auto EGG",_false, function(value)
_G.EGG = value
end)

spawn(function()
    while wait() do
        if _G.EGG then

local A_1 = 
{
	[1] = "Zaruto Tier", 
	[2] = 1
}
local Event = game:GetService("ReplicatedStorage").Assets.Events["buy a egg"]
Event:InvokeServer(A_1)


        end
    end
end)

page1:Toggle("Auto Accept queat",_false, function(value)
_G.Acceptqueat = value
end)

spawn(function()
    while wait() do
        if _G.Acceptqueat then

local A_1 = 
{
	[1] = "Spawn"
}
local Event = game:GetService("ReplicatedStorage").Assets.Events["start a quest"]
Event:FireServer(A_1)

local A_1 = 
{
	[1] = "Spawn"
}
local Event = game:GetService("ReplicatedStorage").Assets.Events["complete a quest"]
Event:FireServer(A_1)

        end
    end
end)

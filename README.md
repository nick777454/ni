local fenv = getfenv()
local _ = fenv.UhAPkh9yYgZugp
local _ = fenv.Sl2pkvD7SLPbrt
local _ = fenv["3KNGoYTTfW1JR5"]
local _ = fenv.Vw5BKvWQgph3
local _Players6 = game:GetService("Players")
local _ReplicatedStorage7 = game:GetService("ReplicatedStorage")
game:GetService("TweenService")
game:GetService("TeleportService")
game:GetService("UserInputService")
game:GetService("VirtualUser")
local _Workspace12 = game:GetService("Workspace")
local _LocalPlayer13 = _Players6.LocalPlayer
_LocalPlayer13:FindFirstChild("leaderstats")
local _leaderstats16 = _LocalPlayer13.leaderstats
_leaderstats16:FindFirstChild("Inventory")
local _LocalPlayer19 = _Players6.LocalPlayer
local _Character20 = _LocalPlayer19.Character
_Character20:WaitForChild("HumanoidRootPart")
local _call24 = _Workspace12:WaitForChild("__Main")
local _call26 = _call24:WaitForChild("__Enemies")
local _call28 = _call26:WaitForChild("Client")
local _call30 = _Workspace12:WaitForChild("__Main")
local _call32 = _call30:WaitForChild("__Enemies")
_call32:WaitForChild("Server")
local _call36 = _Workspace12:WaitForChild("__Main")
_call36:WaitForChild("__Dungeon")
local _call40 = _ReplicatedStorage7:WaitForChild("BridgeNet2")
local _call42 = _call40:WaitForChild("dataRemoteEvent")
_Workspace12:FindFirstChild("__Extra")
local __Extra45 = _Workspace12.__Extra
__Extra45:FindFirstChild("__Appear")
Vector3.new(3848.7985839844, 60.115329742432, 3071.5458984375)
CFrame.new(5462.841796875, 40.822052001953, - 132.91865539551)
CFrame.new(199.86701965332, 33.896511077881, - 5077.1762695312)
CFrame.new(2990.4548339844, 68.842933654785, - 3085.1677246094)
CFrame.new(76.284004211426, 37.853149414062, 4911.2915039062)
local _ = fenv.U6vGBkpuD4Pg
local _CharacterAdded59 = _LocalPlayer19.CharacterAdded
local _ = fenv.Du82dNYrjIn67t
_CharacterAdded59:Connect(function(_62, _62_2, _62_3)
    _62:WaitForChild("HumanoidRootPart")
end)
loadstring(game:HttpGet("https://raw.githubusercontent.com/PZYXF008974/SSURFETIC88965/refs/heads/main/aa"))()
local _71 = loadstring(game:HttpGet("https://github.com/1dontgiveaf/Fluent/releases/latest/download/main.lua"))()
local _74 = loadstring(game:HttpGet("https://raw.githubusercontent.com/1dontgiveaf/Fluent/main/Addons/SaveManager.lua"))()
loadstring(game:HttpGet("https://raw.githubusercontent.com/1dontgiveaf/Fluent/main/Addons/InterfaceManager.lua"))()
local _MarketplaceService78 = game:GetService("MarketplaceService")
local _call87 = _71:CreateWindow({
    SubTitle = "By Perfectus",
    Title = _MarketplaceService78:GetProductInfo(6961824067).Name,
    MinimizeKey = Enum.KeyCode.LeftControl,
    Theme = "Darker",
    Acrylic = false,
    TabWidth = 160,
    Size = UDim2.fromOffset(550, 400),
})
local _call89 = _call87:AddTab({
    Title = "Updates",
    Icon = "http://www.roblox.com/asset/?id=74923711044661",
})
local _call91 = _call87:AddTab({
    Title = "Main",
    Icon = "http://www.roblox.com/asset/?id=18589602613",
})
local _call93 = _call87:AddTab({
    Title = "Dungeon",
    Icon = "http://www.roblox.com/asset/?id=93827869163157",
})
local _call95 = _call87:AddTab({
    Title = "Castle",
    Icon = "http://www.roblox.com/asset/?id=104843346344653",
})
local _call97 = _call87:AddTab({
    Title = "Rank",
    Icon = "http://www.roblox.com/asset/?id=131936181646360",
})
_call87:AddTab({
    Title = "Webhook",
    Icon = "http://www.roblox.com/asset/?id=137207648669220",
})
local _call101 = _call87:AddTab({
    Title = "Teleports",
    Icon = "http://www.roblox.com/asset/?id=18589871232",
})
_call87:AddTab({
    Title = "Mount",
    Icon = "http://www.roblox.com/asset/?id=100203963863969",
})
_call87:AddTab({
    Title = "Pets",
    Icon = "http://www.roblox.com/asset/?id=18589632140",
})
_call87:AddTab({
    Title = "Weapons",
    Icon = "http://www.roblox.com/asset/?id=123555332812660",
})
_call87:AddTab({
    Title = "Player",
    Icon = "http://www.roblox.com/asset/?id=18589827814",
})
_call87:AddTab({
    Title = "Settings",
    Icon = "settings",
})
local _Options112 = _71.Options
_call89:AddSection("WEBSITE LINK")
local _ = fenv.qrt4qTE1keGCC3
_call89:AddButton({
    Callback = function(_117, _117_2, _117_3)
        setclipboard("https://perfectusmim1.github.io/websitem.git
.io/")
        _71:Notify({
            Duration = 3,
            Title = "Perfectus",
            Content = "Copied to clipboard!",
        })
    end,
    Title = "Website Link",
    Description = "",
})
_call89:AddSection("https://discord.gg/fgfAu7dCuG")
local _ = fenv.jjIE9N6UyaoNZ
_call89:AddButton({
    Callback = function(_126, _126_2, _126_3)
        setclipboard("https://discord.com/invite/FcFkuF4xR3")
        _71:Notify({
            Duration = 3,
            Title = "Perfectus",
            Content = "Copied to clipboard!",
        })
    end,
    Title = "https://discord.gg/fgfAu7dCuG",
    Description = "",
})
_call89:AddSection("Update History")
_call89:AddParagraph({
    Title = "v2.0 - 4.09.2025",
    Content = "• Auto Farm Dungeon system completely revamped \n• Auto Castle system added \n• Auto Raid coming soon \n• New mob farm system added \n• New farm options added \n• Teleports are now faster \n• Pets teleport with us \n• Big and small options for farming coming soon \n• Webhook added but not tested, will be improved with updates \n• Most bugs fixed \n• Priority order added for dungeon and castle \n• Loop problems eliminated",
})
_call89:AddParagraph({
    Title = "v1.9 - 4.04.2025",
    Content = "• Added Auto Farm Nearest Walk \n• Fixed Teleports \n• Fixed Auto Find Mount \n• Added toggle coordination between farm methods \n• Added Gamepass Unlock",
})
_call89:AddParagraph({
    Title = "v1.8 - 4.04.2025",
    Content = "• Removed Auto Farm Nearest \n• Added new Auto Farm V2 \n• Removed unnecessary features \n• Minor improvements \n• Added new Bug Report and Suggestion inputs",
})
_call89:AddParagraph({
    Title = "v1.7 - 3.04.2025",
    Content = "• Auto Farm Nearest game crash issue has been fixed. \n• Other bug fixed.",
})
_call89:AddParagraph({
    Title = "v1.6.1 - 2.04.2025",
    Content = "• Added Website Tab  \n• Bug Fixed",
})
_call89:AddParagraph({
    Title = "v1.6 - 2.04.2025",
    Content = "• Updated Auto Rank (Dungeon Tab) \n• Improved overall performance \n• Added Get Gamepass feature \n• Fixed issue with Auto Rank not finding mobs \n• Auto Click now activates automatically",
})
_call89:AddParagraph({
    Title = "v1.5 - 1.04.2025",
    Content = "• Added Auto Rank (Dungeon Tab) \n• Improved overall performance",
})
_call89:AddParagraph({
    Title = "v1.4 - 1.04.2025",
    Content = "• Fixed multi dropdown selection\n• Optimized auto arise/destroy slow systems\n• Improved overall performance",
})
_call91:AddSection("Bug Report")
local _ = fenv.syn
local _ = fenv.KRNL_LOADED
local _ = fenv.fluxus
local _ = fenv.ElectronFunction
local _ = fenv.SUaUrhJstQz3f
local _ = fenv.Fi9617tLg42VhE
local _ = fenv.DateTime
_call91:AddInput("BugReport", {
    Placeholder = "Describe the bug here...",
    Title = "Report a Bug",
    Numeric = false,
    Finished = true,
    Callback = function(_153, _153_2, _153_3)
        local _MarketplaceService154 = game:GetService("MarketplaceService")
        local _ = _MarketplaceService154:GetProductInfo(6961824067).Name
        local _ = game.Players.LocalPlayer.Name
        local _RbxAnalyticsService165 = game:GetService("RbxAnalyticsService")
        _RbxAnalyticsService165:GetClientId()
    end,
    Default = "",
})
_call91:AddSection("Suggestion")
_call91:AddInput("Suggestion", {
    Placeholder = "Type your suggestion here...",
    Title = "Make a Suggestion",
    Numeric = false,
    Finished = true,
    Callback = function(_174, _174_2, _174_3)
        local _ = game.Players.LocalPlayer.Name
        local _MarketplaceService177 = game:GetService("MarketplaceService")
        local _ = _MarketplaceService177:GetProductInfo(6961824067).Name
    end,
    Default = "",
})
_call91:AddSection("Farm Settings")
local _ = fenv.NLXJGugmqblELw
_call91:AddButton({
    Callback = function(_185, _185_2, _185_3)
        local _LocalPlayer187 = game:GetService("Players").LocalPlayer
        local _call189 = _LocalPlayer187:FindFirstChild("leaderstats")
        local _call191 = _call189:FindFirstChild("Passes")
        _call191:SetAttribute("AutoAttack", true)
        _call191:SetAttribute("AutoClicker", true)
        _call191:SetAttribute("DoubleCoins", true)
        _call191:SetAttribute("DoubleExp", true)
        _call191:SetAttribute("DoubleGems", true)
        _call191:SetAttribute("ExtraEquip", true)
        _call191:SetAttribute("ExtraRise", true)
        _call191:SetAttribute("InstaDestroy", true)
        _call191:SetAttribute("InstaArise", true)
        _71:Notify({
            Duration = 3,
            Title = "Perfectus",
            Content = "Gamepass received successfully.",
        })
    end,
    Title = "Get Gamepass",
    Description = "",
})
local _ = fenv.e5qHpgNjoM6Id
_call91:AddDropdown("MovementMethod", {
    Title = "Method",
    Default = 2,
    Multi = false,
    Callback = function(_215, _215_2, _215_3)
    end,
    Values = {
        [1] = "Tween",
        [2] = "Teleport",
        [3] = "Walk",
    },
})
local _ = fenv.EePPj0AGkebl3v
_call91:AddDropdown("FarmType", {
    Title = "Farm Type",
    Default = "Normal",
    Multi = false,
    Callback = function(_219, _219_2, _219_3)
    end,
    Values = {
        [1] = "Normal",
        [2] = "Nearest",
        [3] = "Highest HP",
    },
})
local _ = fenv["4SmimJjhDNWx"]
_call91:AddSlider("Slider", {
    Min = 0,
    Title = "Farm Delay",
    Default = 0,
    Max = 5,
    Description = "",
    Callback = function(_223, _223_2, _223_3)
    end,
    Rounding = 1,
})
_call91:AddSection("Auto Farm")
for _229, _229_2 in _call28:GetChildren() do
    _229_2:IsA("Model")
    _229_2:FindFirstChild("HealthBar")
    local _call235 = _229_2:FindFirstChild("HealthBar")
    _call235:FindFirstChild("Main")
    local _Main238 = _call235.Main
    _Main238:FindFirstChild("Title")
    local _Title242 = _call235.Main.Title
    _Title242:IsA("TextLabel")
end
local _ = fenv.YUsJ303MvvCxY9
local _call248 = _call91:AddDropdown("MobDropdown", {
    Title = "Select Mobs",
    Default = {
},
    Multi = true,
    Values = {
        [1] = _Title242.ContentText,
    },
    Description = "",
})
_G.selectedMobs = {
    [1] = _252,
}
local _ = fenv.kBvcG321OX1WP
_call248:OnChanged(function(_251, _251_2, _251_3)
    for _252, _252_2 in _251 do
    end
end)
local _ = fenv.Izz2xNtfLug6O
_call91:AddButton({
    Callback = function(_256, _256_2, _256_3)
        for _259, _259_2 in _call28:GetChildren() do
            _259_2:IsA("Model")
            _259_2:FindFirstChild("HealthBar")
            local _call265 = _259_2:FindFirstChild("HealthBar")
            _call265:FindFirstChild("Main")
            local _Main268 = _call265.Main
            _Main268:FindFirstChild("Title")
            local _Title272 = _call265.Main.Title
            _Title272:IsA("TextLabel")
        end
        _call248:SetValues({
            [1] = _Title272.ContentText,
        })
        print("Mob list refreshed, found 1 mobs")
    end,
    Title = "Refresh Mob List",
    Description = "",
})
_G.selectedMobs = {
}
_G.mobKillCounts = {
}
_G.currentMobIndex = 1
local _ = fenv.shNruvN7NnaSZK
_call91:AddToggle("FarmSelectedMob", {
    Callback = function(_282, _282_2, _282_3)
        task.spawn(function(_284, _284_2, _284_3)
        end)
    end,
    Title = "Farm Selected Mobs",
    Default = false,
})
local _ = fenv.FEPXJTzRyptwcx
_call91:AddToggle("AutoFarmAllMobs", {
    Callback = function(_288, _288_2, _288_3)
        task.spawn(function(_290, _290_2, _290_3)
        end)
    end,
    Title = "Auto Farm All Mobs",
    Default = false,
})
_call91:AddSection("Auto Attack")
local __Main296 = _Workspace12.__Main
local __Pets297 = __Main296.__Pets
local _call300 = __Pets297:WaitForChild(game:GetService("Players").LocalPlayer.UserId)
local _call302 = _call300:GetChildren()
require(game:GetService("ReplicatedStorage").BridgeNet2).ReferenceBridge("PET_EVENT")
local _ = fenv.YldpGWKejYlZC
local _call309 = _call91:AddSlider("Slider", {
    Min = 0,
    Title = "Auto Attack Range",
    Default = 30,
    Max = 120,
    Description = "",
    Callback = function(_310, _310_2, _310_3)
    end,
    Rounding = 1,
})
local _ = fenv.WRo1aFjfROHZev
_call309:OnChanged(function(_314, _314_2, _314_3)

end)
local _call317 = _call91:AddToggle("MyToggleMain1", {
    Title = "Auto Attack",
    Default = false,
})
_call317:OnChanged(function(_320, _320_2, _320_3)
    local _ = _Options112.MyToggleMain1.Value
    local _ = _call300:GetChildren()[1]
    local _ = _Options112.MyToggleMain1.Value
    local _ = _call300:GetChildren()[1]
    local _ = _Options112.MyToggleMain1.Value
    for _333, _333_2 in _call302 do
        _333_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _340, _340_2 in _call302 do
        _340_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _347, _347_2 in _call302 do
        _347_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _354, _354_2 in _call302 do
        _354_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _361, _361_2 in _call302 do
        _361_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _368, _368_2 in _call302 do
        _368_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _375, _375_2 in _call302 do
        _375_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _382, _382_2 in _call302 do
        _382_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _389, _389_2 in _call302 do
        _389_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _396, _396_2 in _call302 do
        _396_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _403, _403_2 in _call302 do
        _403_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _410, _410_2 in _call302 do
        _410_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _417, _417_2 in _call302 do
        _417_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _424, _424_2 in _call302 do
        _424_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _431, _431_2 in _call302 do
        _431_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _438, _438_2 in _call302 do
        _438_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _445, _445_2 in _call302 do
        _445_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _452, _452_2 in _call302 do
        _452_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _459, _459_2 in _call302 do
        _459_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _466, _466_2 in _call302 do
        _466_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _473, _473_2 in _call302 do
        _473_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _480, _480_2 in _call302 do
        _480_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _487, _487_2 in _call302 do
        _487_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _494, _494_2 in _call302 do
        _494_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _501, _501_2 in _call302 do
        _501_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _508, _508_2 in _call302 do
        _508_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _515, _515_2 in _call302 do
        _515_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _522, _522_2 in _call302 do
        _522_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _529, _529_2 in _call302 do
        _529_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _536, _536_2 in _call302 do
        _536_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _543, _543_2 in _call302 do
        _543_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _550, _550_2 in _call302 do
        _550_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _557, _557_2 in _call302 do
        _557_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _564, _564_2 in _call302 do
        _564_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _571, _571_2 in _call302 do
        _571_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _578, _578_2 in _call302 do
        _578_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _585, _585_2 in _call302 do
        _585_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _592, _592_2 in _call302 do
        _592_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _599, _599_2 in _call302 do
        _599_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _606, _606_2 in _call302 do
        _606_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _613, _613_2 in _call302 do
        _613_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _620, _620_2 in _call302 do
        _620_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _627, _627_2 in _call302 do
        _627_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _634, _634_2 in _call302 do
        _634_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _641, _641_2 in _call302 do
        _641_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _648, _648_2 in _call302 do
        _648_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _655, _655_2 in _call302 do
        _655_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _662, _662_2 in _call302 do
        _662_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _669, _669_2 in _call302 do
        _669_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _676, _676_2 in _call302 do
        _676_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _683, _683_2 in _call302 do
        _683_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _690, _690_2 in _call302 do
        _690_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _697, _697_2 in _call302 do
        _697_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _704, _704_2 in _call302 do
        _704_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _711, _711_2 in _call302 do
        _711_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _718, _718_2 in _call302 do
        _718_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _725, _725_2 in _call302 do
        _725_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _732, _732_2 in _call302 do
        _732_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _739, _739_2 in _call302 do
        _739_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _746, _746_2 in _call302 do
        _746_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _753, _753_2 in _call302 do
        _753_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _760, _760_2 in _call302 do
        _760_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _767, _767_2 in _call302 do
        _767_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _774, _774_2 in _call302 do
        _774_2:GetAttribute("Target")
        print(1)
    end
    print("total rest")
    local _ = _Options112.MyToggleMain1.Value
    for _781, _781_2 in _call302 do
        _781_2:GetAttribute("Target")
        print(1)
    end
end)
_call91:AddSection("Auto Arise, Destroy")
local _call789 = _call91:AddToggle("MyToggleMain2", {
    Title = "Auto Arise",
    Default = false,
})
local _ = fenv.R2q0g620nblO
fenv.connection = _call800
local _ = fenv.jSd4XVTkOIcns
_call789:OnChanged(function(_792, _792_2, _792_3)
    local _ = _Options112.MyToggleMain2.Value
    local __Main795 = _Workspace12.__Main
    local __Enemies796 = __Main795.__Enemies
    local _DescendantAdded798 = __Enemies796.Client.DescendantAdded
    _DescendantAdded798:Connect(function(_801, _801_2, _801_3)
        _801:IsA("ProximityPrompt")
        local _ = _801.Name
    end)
end)
local _call808 = _call91:AddToggle("MyToggleMain3", {
    Title = "Auto Destroy",
    Default = false,
})
local _ = fenv.IR2pHC5WjsqBI
fenv.connection = _call819
local _ = fenv.GIElf6N3VKMdBW
_call808:OnChanged(function(_811, _811_2, _811_3)
    local _ = _Options112.MyToggleMain3.Value
    local __Main814 = _Workspace12.__Main
    local __Enemies815 = __Main814.__Enemies
    local _DescendantAdded817 = __Enemies815.Client.DescendantAdded
    _DescendantAdded817:Connect(function(_820, _820_2, _820_3)
        _820:IsA("ProximityPrompt")
        local _ = _820.Name
    end)
end)
_call97:AddSection("Auto Rank")
_call97:AddParagraph({
    Title = "Current Rank",
    Content = "Rank: " .. game:GetService("Players").LocalPlayer.leaderstats.Rank.Value,
})
local _ = fenv.O348DTlxpv9DcZ
local _ = fenv.mQG0AAQQ014TpL
local _ = fenv.qtZz63M2gTGYGC
local _ = fenv["1eOgiRTqiAyIo"]
_call97:AddToggle("AutoRankToggle", {
    Callback = function(_838, _838_2, _838_3)
        local _LocalPlayer840 = game:GetService("Players").LocalPlayer
        _LocalPlayer840:SetAttribute("AutoClick", true)
        task.spawn(function(_844, _844_2, _844_3)
            local __Main845 = _Workspace12.__Main
            __Main845:FindFirstChild("Room_1")
            for _850, _850_2 in _call28:GetChildren() do
                _850_2:IsA("Model")
                _850_2:FindFirstChild("HumanoidRootPart")
                local _ = _850_2.Name
                local _ = _850_2.Parent
                local _call858 = _850_2:FindFirstChild("HealthBar")
                _call858:FindFirstChild("Main")
                local _Main861 = _call858.Main
                _Main861:FindFirstChild("Bar")
                local _Bar865 = _call858.Main.Bar
                local _call867 = _Bar865:FindFirstChild("Amount")
                _call867:IsA("TextLabel")
                local _ = _call867.ContentText
                local _ = _850_2.Parent
                local _ = _850_2.Name
                local _ = _850_2.Parent
                local _gamePlayersLocalPlayer876 = game.Players.LocalPlayer
                local _ = _gamePlayersLocalPlayer876.Character
                local _Character878 = _gamePlayersLocalPlayer876.Character
                local _call880 = _Character878:FindFirstChild("CharacterScripts")
                local _call882 = _call880:FindFirstChild("FlyingFixer")
                _call882:Destroy()
                local _call886 = _call880:FindFirstChild("CharacterUpdater")
                _call886:Destroy()
                local _Position891 = _850_2.HumanoidRootPart.Position
                _call64.CFrame = CFrame.new(_Position891 - _850_2.HumanoidRootPart.CFrame.LookVector * 5, _Position891)
                local _LocalPlayer900 = game:GetService("Players").LocalPlayer
                _LocalPlayer900:SetAttribute("PetsArise", false)
                local _LocalPlayer904 = game:GetService("Players").LocalPlayer
                _LocalPlayer904:SetAttribute("PetsArise", true)
                local _call911 = require(game:GetService("ReplicatedStorage").BridgeNet2).ReferenceBridge("PET_EVENT")
                _call911:Fire({
                    PetPos = "",
                    AttackType = "All",
                    Event = "Attack",
                    Enemy = _850_2.Name,
                })
                _call42:FireServer({
                    [1] = {
                        PetPos = {
},
                        AttackType = "All",
                        Event = "Attack",
                        Enemy = _850_2.Name,
                    },
                    [2] = "",
                })
                local _ = _850_2.Parent
                local _ = _850_2.Parent
                local _call921 = _850_2:FindFirstChild("HealthBar")
                _call921:FindFirstChild("Main")
                local _Main924 = _call921.Main
                _Main924:FindFirstChild("Bar")
                local _Bar928 = _call921.Main.Bar
                local _call930 = _Bar928:FindFirstChild("Amount")
                _call930:IsA("TextLabel")
                local _ = _call930.ContentText
                local _ = _850_2.Parent
                local _ = _850_2.Name
                local _ = _850_2.Parent
                local _ = _850_2.Parent
                local _call939 = _850_2:FindFirstChild("HealthBar")
                _call939:FindFirstChild("Main")
                local _Main942 = _call939.Main
                _Main942:FindFirstChild("Bar")
                local _Bar946 = _call939.Main.Bar
                local _call948 = _Bar946:FindFirstChild("Amount")
                _call948:IsA("TextLabel")
                local _ = _call948.ContentText
                local _ = _850_2.Parent
                local _ = _850_2.Name
                local _ = _850_2.Parent
                local _ = _850_2.Parent
                local _call957 = _850_2:FindFirstChild("HealthBar")
                _call957:FindFirstChild("Main")
                local _Main960 = _call957.Main
                _Main960:FindFirstChild("Bar")
                local _Bar964 = _call957.Main.Bar
                local _call966 = _Bar964:FindFirstChild("Amount")
                _call966:IsA("TextLabel")
                local _ = _call966.ContentText
                local _ = _850_2.Parent
                local _ = _850_2.Name
                local _ = _850_2.Parent
                local _ = _850_2.Parent
                local _call975 = _850_2:FindFirstChild("HealthBar")
                _call975:FindFirstChild("Main")
                local _Main978 = _call975.Main
                _Main978:FindFirstChild("Bar")
                local _Bar982 = _call975.Main.Bar
                local _call984 = _Bar982:FindFirstChild("Amount")
                _call984:IsA("TextLabel")
                local _ = _call984.ContentText
                local _ = _850_2.Parent
                local _ = _850_2.Name
                local _ = _850_2.Parent
                local _ = _850_2.Parent
                local _call993 = _850_2:FindFirstChild("HealthBar")
                _call993:FindFirstChild("Main")
                local _Main996 = _call993.Main
                _Main996:FindFirstChild("Bar")
                local _Bar1000 = _call993.Main.Bar
                local _call1002 = _Bar1000:FindFirstChild("Amount")
                _call1002:IsA("TextLabel")
                local _ = _call1002.ContentText
                local _ = _850_2.Parent
                local _ = _850_2.Name
                local _ = _850_2.Parent
                local _ = _850_2.Parent
                local _call1011 = _850_2:FindFirstChild("HealthBar")
                _call1011:FindFirstChild("Main")
                local _Main1014 = _call1011.Main
                _Main1014:FindFirstChild("Bar")
                local _Bar1018 = _call1011.Main.Bar
                local _call1020 = _Bar1018:FindFirstChild("Amount")
                _call1020:IsA("TextLabel")
                local _ = _call1020.ContentText
                local _ = _850_2.Parent
                local _ = _850_2.Name
                local _ = _850_2.Parent
                local _ = _850_2.Parent
                local _call1029 = _850_2:FindFirstChild("HealthBar")
                _call1029:FindFirstChild("Main")
            end
        end)
    end,
    Title = "Auto Rank",
    Default = false,
})
_call93:AddParagraph({
    Title = "Priority Information",
    Content = "Select your primary and secondary priorities below.\nThe script will focus on the primary task first,\nthen move to the secondary when the primary is unavailable.\nRaid detection runs in the background regardless of priority.",
})
_call93:AddSection("Auto Dungeon Search")
local _ = fenv.hGjZJQvvlBdxcQ
_call93:AddDropdown("WorldSelection", {
    Title = "Select Worlds",
    Default = {
},
    Multi = true,
    Callback = function(_1040, _1040_2, _1040_3)
        for _1041, _1041_2 in _1040 do
        end
    end,
    Values = {
        [1] = "Leveling City",
        [2] = "Grass Village",
        [3] = "Brum Island",
        [4] = "Faceheal Town",
        [5] = "Lucky Kingdom",
        [6] = "Nipon City",
        [7] = "Mori Town",
    },
})
local _ = fenv.GWZGtSAdT11XP
_call93:AddDropdown("RankSelection", {
    Title = "Select Ranks",
    Default = {
},
    Multi = true,
    Callback = function(_1045, _1045_2, _1045_3)
        for _1046, _1046_2 in _1045 do
        end
    end,
    Values = {
        [1] = "E",
        [2] = "D",
        [3] = "C",
        [4] = "B",
        [5] = "A",
        [6] = "S",
        [7] = "SS",
    },
})
local _ = fenv.rUj4WZM8kxSZrh
_call93:AddDropdown("DungeonTypeDropdown", {
    Title = "Dungeon Type",
    Default = {
},
    Multi = true,
    Callback = function(_1050, _1050_2, _1050_3)
        for _1051, _1051_2 in _1050 do
        end
    end,
    Values = {
        [1] = "Normal Dungeon",
        [2] = "Red Dungeon",
    },
})
local _ = fenv.qpJ24hnyslP4nb
_call93:AddDropdown("DungeonSearchMethod", {
    Title = "Dungeon Search Method",
    Default = "Warn Text",
    Multi = false,
    Callback = function(_1055, _1055_2, _1055_3)
        print("[DEBUG] Selected dungeon search method:", _1055)
    end,
    Values = {
        [1] = "Warn Text",
        [2] = "Teleport",
    },
})
local _ = fenv.rxsxMO47i5m3J
local _ = fenv.JcJq7mtdfXrf4
local _ = fenv.BqT3sVWtsMei
_call93:AddToggle("AutoSearchDungeon", {
    Callback = function(_1060, _1060_2, _1060_3)
        local _ = _Options112.DungeonSearchMethod.Value
        task.spawn(function(_1064, _1064_2, _1064_3)
        end)
    end,
    Title = "Auto Search Dungeon",
    Default = false,
})
local _ = fenv["2PMIAV8H0amrn"]
_call93:AddToggle("AutoBuyTicket", {
    Callback = function(_1070, _1070_2, _1070_3)
    end,
    Title = "Auto Buy Ticket",
    Default = false,
})
local _ = fenv.PfzWnm1wrShk
local _ = fenv["99CQr7hytL9OAO"]
_call93:AddToggle("TeleportMobs", {
    Callback = function(_1074, _1074_2, _1074_3)
        task.spawn(function(_1076, _1076_2, _1076_3)
        end)
        local _LocalPlayer1079 = game:GetService("Players").LocalPlayer
        _LocalPlayer1079:SetAttribute("AutoClick", true)
    end,
    Title = "Auto Farm Dungeon",
    Default = false,
})
_call93:AddSection("Dungeon Position Management")
local _ = fenv.hlBr9M9oibiy
fenv._ = "SoloWorld"
local _ = fenv.N2LyqIF2CCRJV
local _ = fenv.gHUwpDMiSB3w
_call93:AddButton({
    Callback = function(_1087, _1087_2, _1087_3)
        local _ = _LocalPlayer19.Character
        local _Character1089 = _LocalPlayer19.Character
        _Character1089:FindFirstChild("HumanoidRootPart")
        local _CFrame1094 = _LocalPlayer19.Character.HumanoidRootPart.CFrame
        local _call1096 = _Workspace12:WaitForChild("__Main")
        local _call1098 = _call1096:WaitForChild("__Enemies")
        local _call1100 = _call1098:WaitForChild("Server")
        local _call1102 = _call1100:FindFirstChild("1")
        for _1105, _1105_2 in _call1102:GetChildren() do
            _1105_2:IsA("Part")
            print("[DEBUG] Detected world:", "Leveling City")
            _74:Save("DungeonReturnPosition", {
                world = "Leveling City",
                cframe = {
                    lookVectorY = _CFrame1094.LookVector.Y,
                    upVectorZ = _CFrame1094.UpVector.Z,
                    y = _CFrame1094.Y,
                    x = _CFrame1094.X,
                    upVectorX = _CFrame1094.UpVector.X,
                    z = _CFrame1094.Z,
                    lookVectorZ = _CFrame1094.LookVector.Z,
                    upVectorY = _CFrame1094.UpVector.Y,
                    lookVectorX = _CFrame1094.LookVector.X,
                },
            })
            _71:Notify({
                Duration = 5,
                Title = "Dungeon Position Saved",
                Content = "Return position saved in Leveling City",
            })
        end
    end,
    Title = "Save Dungeon Return Position",
    Description = "Saves current position to return after dungeon",
})
local _ = fenv["7406EPR2KDeV"]
_call93:AddToggle("ReturnAfterDungeon", {
    Callback = function(_1133, _1133_2, _1133_3)
    end,
    Title = "Return After Dungeon",
    Default = false,
})
_call93:AddSection("Primary")
local _ = fenv.GELsT2Nz0mi2
_call93:AddDropdown("PrioritySelection", {
    Title = "Primary Priority",
    Default = "Dungeon",
    Multi = false,
    Callback = function(_1139, _1139_2, _1139_3)
    end,
    Values = {
        [1] = "Dungeon",
        [2] = "Castle",
        [3] = "Raid",
    },
})
local _ = fenv.K6AK1rjz5878Xv
_call93:AddDropdown("SecondaryPriority", {
    Title = "Secondary Priority",
    Default = "Castle",
    Multi = false,
    Callback = function(_1143, _1143_2, _1143_3)
    end,
    Values = {
        [1] = "Dungeon",
        [2] = "Castle",
        [3] = "Raid",
    },
})
_call95:AddSection("Auto Castle Farm")
local _ = fenv.EbWAh3P7ATIk
_call95:AddToggle("CastleFarm", {
    Callback = function(_1149, _1149_2, _1149_3)
        task.spawn(function(_1151, _1151_2, _1151_3)
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
            tick()
        end)
    end,
    Title = "Auto Farm Castle",
    Default = false,
})
local _ = fenv.USEj9Gy0lSfQ0
_call95:AddInput("ExitFloor", {
    Placeholder = "Enter floor (1-100)",
    Title = "Exit at Floor",
    Default = "100",
    Numeric = true,
    Finished = true,
    Callback = function(_1223, _1223_2, _1223_3)
    end,
    Description = "Enter floor number (max 100)",
})
_call101:AddSection("World Teleports")
local _ = fenv.DOeOpIuW3K0Id
local _ = fenv.Viz2iDRxeRP61h
_call101:AddButton({
    Callback = function(_1229, _1229_2, _1229_3)
        _call42:FireServer({
            [1] = {
                Event = "ChangeSpawn",
                Spawn = "OPWorld",
            },
            [2] = "\n",
        })
        local _ = game.Players.LocalPlayer.Character
        local _Character1235 = game.Players.LocalPlayer.Character
        _Character1235:BreakJoints()
    end,
    Title = "Brum Island",
    Description = "Teleport to Brum Island",
})
local _ = fenv.We99om2Mmne6OK
_call101:AddButton({
    Callback = function(_1242, _1242_2, _1242_3)
        _call42:FireServer({
            [1] = {
                Event = "ChangeSpawn",
                Spawn = "NarutoWorld",
            },
            [2] = "\n",
        })
        local _ = game.Players.LocalPlayer.Character
        local _Character1248 = game.Players.LocalPlayer.Character
        _Character1248:BreakJoints()
    end,
    Title = "Grass Village",
    Description = "Teleport to Grass Village",
})
local _ = fenv.PBGroJUKDb8w
_call101:AddButton({
    Callback = function(_1254, _1254_2, _1254_3)
        _call42:FireServer({
            [1] = {
                Event = "ChangeSpawn",
                Spawn = "SoloWorld",
            },
            [2] = "\n",
        })
        local _ = game.Players.LocalPlayer.Character
        local _Character1260 = game.Players.LocalPlayer.Character
        _Character1260:BreakJoints()
    end,
    Title = "Solo City",
    Description = "Teleport to Solo City",
})
local _ = fenv["3ZWqpz1OK3TjA"]
_call101:AddButton({
    Callback = function(_1266, _1266_2, _1266_3)
        _call42:FireServer({
            [1] = {
                Event = "ChangeSpawn",
                Spawn = "BleachWorld",
            },
            [2] = "\n",
        })
        local _ = game.Players.LocalPlayer.Character
        local _Character1272 = game.Players.LocalPlayer.Character
        _Character1272:BreakJoints()
    end,
    Title = "Faceheal Town",
    Description = "Teleport to Faceheal Town",
})
_call101:AddButton({
    Callback = function(_1278, _1278_2, _1278_3)
        _call42:FireServer({
            [1] = {
                Event = "ChangeSpawn",
                Spawn = "BCWorld",
            },
            [2] = "\n",
        })
        local _ = game.Players.LocalPlayer.Character
        local _ = game.Players.LocalPlayer.Character.BreakJoints
    end,
    Title = "Lucky Island",
    Description = "Teleport to Lucky Island",
})
local _ = _call101.AddButton

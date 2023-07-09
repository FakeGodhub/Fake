local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("e hub", "DarkTheme")


local Tab = Window:NewTab("วาป")
local Section = Tab:NewSection("ฟังชั่น")
Section:NewButton("วาปแมพบ้าน", "คลิกเพื่อวาป", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-12.026423454284668, 3.023024797439575, -61.04216384887695)
end)
Section:NewButton("ส.น", "ไปบ้านตํารวจ", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-120.45864868164062, 3.39802622795105, -6.748726844787598)
end)
Section:NewButton("เสกมอไซ", "เสกรถ", function()
    local args = {
    [1] = "PickingCar",
    [2] = "NPHarleyDavison"
}

game:GetService("ReplicatedStorage").JJ3:FindFirstChild("2NN2Ca2NN2r"):FireServer(unpack(args))

end)
Section:NewButton("เสกรถแรมโบ", "คลิกเพื่อเสกรถ", function()
local args = {
    [1] = "PickingCar",
    [2] = "FordGT"
}

game:GetService("ReplicatedStorage").JJ3:FindFirstChild("2NN2Ca2NN2r"):FireServer(unpack(args))

end)

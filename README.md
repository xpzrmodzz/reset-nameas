local args = {
    [1] = game:GetService("Players").LocalPlayer.Name,
    [2] = "player"
}

game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("nameEvent"):FireServer(unpack(args))

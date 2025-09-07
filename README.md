local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer

while true do
    local character = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()
    local rootPart = character:WaitForChild("HumanoidRootPart")
    rootPart.CFrame = CFrame.new(-76.0261078, 12.0500031, 5341.8335, -1, 0, 0, 0, 1, 0, 0, 0, -1)) -- Teleport to (-76.0261078, 12.0500031, 5341.8335, -1, 0, 0, 0, 1, 0, 0, 0, -1)) to avoid being inside the baseplate
    task.wait(1) -- Wait 1 second before teleporting again
end


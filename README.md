_G.AutoLIft = true

while _G.AutoLIft = true do
task .wait(0.0000000001)
game:GetService("ReplicatedStorage"):FindFirstChild("events-shared/network@GlobalEvents").placeBlock:FireServer()
end

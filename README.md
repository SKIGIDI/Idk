# Idk
Idk
while true do

local args = {
	"Cursor",
	100,
	true
}
game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("BuyBuilding"):FireServer(unpack(args))
wait(0)
end

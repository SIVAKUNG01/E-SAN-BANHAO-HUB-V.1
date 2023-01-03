getgenv().key = "Key here!!" -- Input key to use auto execute
_G.Select_Team = "Marine" -- Choose Pirate or Marine
if getgenv().key == nil or getgenv().key == "" or getgenv().key = "Key here!!" then
loadstring(game:HttpGet('https://raw.githubusercontent.com/SIVAKUNG01/E-SAN-BANHAO-HUB-V.1/main/ESAN-TRASH'))()
else
loadstring(game:HttpGet('https://raw.githubusercontent.com/SIVAKUNG01/E-SAN-BANHAO-HUB-V.1/main/ESAN-BOOD'))()
end

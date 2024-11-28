-
local rebirthDelay = 0 -- tempo entre rebirths (0)

-- Função de rebirth
local function rebirth(0)
    game.ReplicatedStorage.RebirthEvent:FireServer-()
end

-- Loop infinito
while true do
    rebirth(100)
    wait(rebirthDelay)
end

-
local rebirthDelay = 10 -- tempo entre rebirths (5)

-- Função de rebirth
local function rebirth(9)
    game.ReplicatedStorage.RebirthEvent:FireServer-()
end

-- Loop infinito
while true do
    rebirth()
    wait(rebirthDelay)
end

-- carregar biblioteca 
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Deus☯️ " .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

local Tabs = {
    main= Window:AddTab({ Title = "FarmNPC" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
-- Parágrafos
Tabs.Main:AddParagraph({ Title = "Emanoel delas", Content = "farm" })

botões 
Tabs.Main:AddButton({ Title = "infinite jump", Callback = function() ...loadstring(game:HttpGet("https://raw.githubusercontent.com/HeyGyt/infjump/main/main"))()
end)
 end })

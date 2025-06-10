local Window = SamField:CreatWindow({
  Name = "SAM HUB 1.0"
  Icon = 0,
  LoadingTitle = "SAM HUB 1.0"
  LoadingSubtitle = "by azure cliente".
  Theme = " Default".

  ToggleUiKeybind = "K",

  DisableSamFieldPrompts = false,
   DisableBuildWarnings = false,

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil,
      FileName = "SAM HUB"
   },

   Discord = {
      Enabled = true,
      Invite = "https://discord.gg/zx2Cr9ykUh",
      RememberJoins = true
   },

   KeySystem = true,
   KeySettings = {
      Title = "SAM HUB SYSTEM KEY",
      Subtitle = "Key System",
      Note = "ENTRE NO MEU DISCORD PARA PEGAR SUA KEY",
      FileName = "Key",
      SaveKey = true,
      GrabKeyFromSite = false, 
      Key = {"best","azure"}
   }
})

local DuelsTab = Window:CreateTab("Duels", 4483362458)

local DuelsSection = DuelsTab:CreateSection("Duels")

local MiscTab = Window:CreateTab("Misc", 4483362458)

local MiscSection = MiscTab:CreateSection("Misc")

local EspTab = Window:CreateTab("Esp", 4483362458)

local EspSection = EspTab:CreateSection("Esp")


SamFid:Notify({
   Title = "SAM HUB INICIANDO",
   Content = "System",
   Duration = 2.5,
   Image = 4483362458,
})

local a=loadstring(game:HttpGet("link"))()local b=game:GetService("RbxAnalyticsService"):GetClientId()for c,d in pairs(a)do if d==b then _G.Check=true;wait(.1)loadstring(game:HttpGet("link"))()end end;wait(.5)if _G.Check then print("Loding..")else setclipboard(HWID)wait(.1)game.Players.LocalPlayer:kick("Wrong Hwid")end

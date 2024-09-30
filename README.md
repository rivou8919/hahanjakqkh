
se game.PlaceId == 2753915549 então
    Mundo1 = verdadeiro
elseif game.PlaceId == 4442272183 então
    Mundo2 = verdadeiro
elseif game.PlaceId == 7449423635 então
    Mundo3 = verdadeiro
outro
    game:GetService("Jogadores").LocalPlayer:Kick("Não dê suporte, aguarde...")
fim

função CheckQuest()
    MeuNível = jogo:GetService("Jogadores").LocalPlayer.Data.Level.Value
    se World1 então
        se MyLevel == 1 ou MyLevel <= 9 então
            Seg = "Bandido"
            LevelQuest = 1
            NomeQuest = "BanditQuest1"
            NomeMon = "Bandido"
            CFrameQuest = CFrame.new(1059.37195, 15.4495068, 1550.4231, 0.939700544, -0, -0.341998369, 0, 1, -0, 0.341998369, 0, 0.939700544)
            CFrameMon = CFrame.new(1045.962646484375, 27.00250816345215, 1560.8203125)
        elseif MeuNível == 10 ou MeuNível <= 14 então
            Seg = "Macaco"
            LevelQuest = 1
            NomeQuest = "JungleQuest"
            NomeMon = "Macaco"
            CFrameQuest = CFra…

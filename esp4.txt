local _1 = game:GetService("\x55\115\x65\162\x49\x6E\x70\x75\x74\x53\145\x72\x76\151\x63\x65")

local _2 = function(_3)
    if _3["\75\145\x79\160\x61\x64\55\x53\x65\166\x65\x6E"] == Enum["\x4B\x65\x79\x63\157\144\x65"]["\75\145\x79\x70\x61\x64\55\x53\x65\x76\x65\156"] or _3["\75\145\x79\160\141\x64\55\x53\x65\x76\x65\x6E"] == Enum["\x4B\145\x79\x63\157\x64\145"]["\x4E\165\155\120\141\144\x37"] then
        _E12 = true
        _F14 = true
        _O15 = true
        _F16 = Color3["\110\x65\x77"](0, 0, 0)
        _O17 = Color3["\x6E\x65\x77"](1, 1, 1)
        _F18 = 1
        _O19 = 0

        local _E20 = game["\x43\x6F\x72\145\107\x75\x69"]:FindFirstChild("\x45\x53\120\x48\157\x6C\x64\145\162") or Instance["\x6E\x65\167"]("\x46\x6F\154\144\x65\x72")
        if _E12 == false then
            _E20:Destroy()
        end

        if _E20["\x4E\141\x6D\x65"] == "\x46\x6F\154\x64\x65\x72" then
            _E20["\x4E\141\x6D\145"] = "\x45\x53\120\110\157\x6C\144\x65\162"
            _E20["\x50\141\162\x65\156\164"] = game["\x43\157\x72\x65\x47\165\x69"]
        end

        if _F14 == false and _E20:FindFirstChild(game["\80\154\141\171\145\162\163"]["\x4C\157\x63\x61\154\120\x6C\141\x79\x65\162"]["\x4E\141\x6D\x65"]) then
            _E20:FindFirstChild(game["\80\154\x61\x79\x65\162\x73"]["\x4C\x6F\x63\141\x6C\x50\x6C\x61\x79\x65\162"]["\x4E\x61\x6D\x65"]):Destroy()
        end

        if _E12 == true then 
            _E12 = false
            _E12 = true
        end

        while _E12 do
            task["\x77\x61\x69\164"]()
            for _, _E21 in pairs(game["\x50\x6C\x61\171\145\x72\163"]:GetChildren()) do
                local _E22 = _E21["

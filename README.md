function scripthub()
    game.Players.LocalPlayer:Kick("Whilelist")
    end
    
    
    local Key = getgenv().key 
    local discordid = getgenv().id 
local ostimec1 = os.time()
local main = {
	["1"] = rconsoleprint,
	["2"] = hookfunc,
	["3"] = hookfunction,
	["4"] = replaceclosure,
	["5"] = setreadonly,
	["6"] = make_writeable,
	["7"] = print,
	["8"] = warn,
	["9"] = writefile,
	["10"] = appendfile,
	["11"] = setclipboard,
}
if getgenv().AntihookFF1 == nil then
	getgenv().AntihookFF1 = {
		["print"] = false, -- ปรับเป็น true =ไห้ไช้ได้
		["hook"] = false
	}
end

local azx 
azx = hookfunc(rconsoleprint, function (...)
	if getgenv().AntihookFF1["print"] == true then
		return azx(...)
	else
		return 
	end
end)
local al 
al = hookfunc(hookfunction, function (...)
	if getgenv().AntihookFF1["hook"] == true then
		return al(...)
	else
		return 
	end
	
end)
local al 
al = hookfunc(setclipboard, function (...)
	if getgenv().AntihookFF1["hook"] == true then
		return al(...)
	else
		return 
	end
end)
local an 
an = hookfunc(replaceclosure, function (...)
	if getgenv().AntihookFF1["print"] == true then
		return an(...)
	else
		return 
	end
	
end)
local ay 
ay = hookfunc(setreadonly, function (...)
	if getgenv().AntihookFF1["hook"] == true then
		return ay(...)
	else
		return 
	end
	
end)
local ae 
ae = hookfunc(make_writeable, function (...)
	if getgenv().AntihookFF1["hook"] == true then
		return ae(...)
	else
		return 
	end
end)
local av 
av = hookfunc(print, function (...)
	if getgenv().AntihookFF1["print"] == true then
		return av(...)
	else
		return 
	end
end)
local at 
at = hookfunc(warn, function (...)
	if getgenv().AntihookFF1["hook"] == true then
		return at(...)
	else
		return 
	end
end)
local aw 
aw = hookfunc(writefile, function (...)
	if getgenv().AntihookFF1["hook"] == true then
		return aw(...)
	else
		return 
	end
end)
local aq
aq = hookfunc(appendfile, function (...)
	if getgenv().AntihookFF1["hook"] == true then
		return aq(...)
	else
		return 
	end
end)
local dsa
dsa = hookfunc(clonefunction,function(...)
    if getgenv().AntihookFF1["hook"] == true then
		return dsa(...)
	else
		return 
	end
end)
local as 
as = hookfunc(hookfunc, function (...)
	if getgenv().AntihookFF1["hook"] == true then
		return as(...)
	else
		return 
	end
end)

getgenv().rconsoleprint = function(...)
	if getgenv().AntihookFF1["print"] == true then
		return main["1"](...)
	else
		return "Secret"
	end
end
getgenv().hookfunc = function(...)
	if getgenv().AntihookFF1["hook"] == true then
		return main["2"](...)
	else
		return "Secret"
	end
end
getgenv().hookfunction = function(...)
	if getgenv().AntihookFF1["hook"] == true then
		return main["3"](...)
	else
		return "Secret"
	end
end
getgenv().replaceclosure = function(...)
	if getgenv().AntihookFF1["hook"] == true then
		return main["4"](...)
	else
		return "Secret"
	end
end
getgenv().setreadonly = function(...)
	if getgenv().AntihookFF1["hook"] == true then
		return main["5"](...)
	else
		return "Secret"
	end
end
getgenv().make_writeable = function(...)
	if getgenv().AntihookFF1["hook"] == true then
		return main["6"](...)
	else
		return "Secret"
	end
end
getgenv().print = function(...)
	if getgenv().AntihookFF1["print"] == true then
		return main["7"](...)
	else
		return "Secret"
	end
end
getgenv().warn = function(...)
	if getgenv().AntihookFF1["print"] == true then
		return main["8"](...)
	else
		return "Secret"
	end
end
getgenv().writefile = function(...)
	if getgenv().AntihookFF1["hook"] == true then
		return main["9"](...)
	else
		return "Secret"
	end
end
getgenv().appendfile = function(...)
	if getgenv().AntihookFF1["hook"] == true then
		return main["10"](...)
	else
		return "Secret"
	end
end
getgenv().setclipboard = function(...)
	if getgenv().AntihookFF1["hook"] == true then
		return main["11"](...)
	else
		return "Secret"
	end
end

spawn(function()
    game:GetService("RunService").RenderStepped:connect(function()
        game.CoreGui.ChildAdded:connect(function(p1)
        	if p1:FindFirstChild("PropertiesFrame") or p1:FindFirstChild("ExplorerPanel") or p1:FindFirstChild("SaveInstance") then -- Dark Dex frames/children
                game.Players.LocalPlayer:Kick("\nTara Hub\n Anti Dark Dex")
                wait(.5)
        		while true do end
        	end
        end)
    end)
end)

function kick(msg)
    game.Players.LocalPlayer:Kick(msg)
end

function kickcash(msg)
    game.Players.LocalPlayer:Kick("\nTara Hub\n"..msg)
    wait(1)
    wait(math.random(1, 10))
    local ts = game:GetService("TeleportService")
    local p = game:GetService("Players").LocalPlayer
    ts:Teleport(game.PlaceId, p)
    wait()
    function cash()
        return
    end
    local FFFF
    FFFF = hookfunc(cash,function(vvvv)
        return FFFF(vvvv)
    end)
    cash()
    getpropvalue()
    while true do end
    for i = 0 , 10000000 do
        while true do end
    end
end

function scripthub()
    game.Players.LocalPlayer:Kick("Whitelist ?")
end

local Key = getgenv().Key
local discord_id = getgenv().DiscordId

if getgenv().Key == nil or getgenv().Key == "" and getgenv().DiscordId == nil or getgenv().DiscordId == "" then
    return kickcash("\n Not found key and discord Id")
end

if getgenv().Key == nil or getgenv().Key == "" then
    return kickcash("\n Not found key")
end

if getgenv().DiscordId == nil or getgenv().DiscordId == "" then
    return kickcash("\n Not found discord Id")
end

function ntf(msg,Delay)  -- เปลียนเป็นชื่อมึงอะ
    game.StarterGui:SetCore("SendNotification",{
    Title = "Tara Hub",
    Icon = "http://www.roblox.com/asset/?id=";
    Text = msg,
    Duration = Delay
    })
end
-------------------------------------- Anti Dev Console and Console Syn x ------------------------------

--[[spawn(function()
    game:GetService("RunService").RenderStepped:connect(function()
        for i,v in pairs (game:GetService("CoreGui"):GetChildren())do
            if v.Name == "DevConsoleMaster" then
                v.Enabled = false
                v:Destroy()
                game.Players.LocalPlayer:Kick("\nXenfer Hub\n Anti Dev Console")
                wait(.5)
                while true do end
            end
        end
    end)
end)

local UIS = game:GetService("UserInputService")
local keydown = false
UIS.InputBegan:Connect(function(Input)
    if Input.KeyCode == Enum.KeyCode.Insert then
        keydown = true
        game.Players.localPlayer:Kick("\nXenfer Hub\n Anti Console Synapse X")

        while true do
        end
    end
end)]]

---------------------------------------------------------------------------------------------

local b = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/' -- You will need this for encoding/decoding
function base64encode(data)
    return ((data:gsub('.', function(x) 
        local r,b='',x:byte()
        for i=8,1,-1 do r=r..(b%2^i-b%2^(i-1)>0 and '1' or '0') end
        return r;
    end)..'0000'):gsub('%d%d%d?%d?%d?%d?', function(x)
        if (#x < 6) then return '' end
        local c=0
        for i=1,6 do c=c+(x:sub(i,i)=='1' and 2^(6-i) or 0) end
        return b:sub(c+1,c+1)
    end)..({ '', '==', '=' })[#data%3+1])
end

-- decoding
function base64decode(data)
    data = string.gsub(data, '[^'..b..'=]', '')
    return (data:gsub('.', function(x)
        if (x == '=') then return '' end
        local r,f='',(b:find(x)-1)
        for i=6,1,-1 do r=r..(f%2^i-f%2^(i-1)>0 and '1' or '0') end
        return r;
    end):gsub('%d%d%d?%d?%d?%d?%d?%d?', function(x)
        if (#x ~= 8) then return '' end
        local c=0
        for i=1,8 do c=c+(x:sub(i,i)=='1' and 2^(8-i) or 0) end
            return string.char(c)
    end))
end

local requesthttps 
if syn then
    requesthttps = syn.request
elseif KRNL_LOADED then
    requesthttps = request
else
    requesthttps = fluxus.request
end

local getserver = requesthttps({
    ["Url"] = "http://ใส่Ip:3000/whitelist?Key="..Key.."&ds="..discord_id, -- ใส่ Ip
    ["Medthod"] = "GET"
})
local getserver2 = requesthttps({
    ["Url"] = "http://ใส่Ip:3000/whitelist?Key="..Key.."&ds="..discord_id, -- ใส่ Ip
    ["Medthod"] = "GET"
})
local gethwid = requesthttps({
    ["Url"] = "http://ใส่Ip:3000/Hwid", -- ใส่ Ip
})
wait(1)
game.CoreGui.ChildAdded:connect(function(q)
    game.RunService.RenderStepped:connect(function()
        if q.Name == "UI LIB" or q.Name == "spyu" then
            while true do end
        end
    end)
end)
function crashzzz(seconds)
    local start = os.time()
    repeat until os.time() > start + seconds
end
crashzzz(3)
local getdata = base64decode(getserver.Body)
if getserver.StatusCode == 200 and gethwid.StatusCode == 200 then
    local datachack = {
    ["-1F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()-1));
    ["-2F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()-2));
    ["-3F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()-3));
    ["-4F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()-4));
    ["-5F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()-5));
    ["-6F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()-6));
    ["-7F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()-7));
    ["-8F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()-8));
    ["-9F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()-9));
    ["-10F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()-10));
    ["1F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()+1));
    ["2F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()+2));
    ["3F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()+3));
    ["4F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()+4));
    ["5F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()+5));
    ["6F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()+6));
    ["7F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()+7));
    ["8F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()+8));
    ["9F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()+9));
    ["10F"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."False"..os.time()+10));
    
    ["1T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()+1));
    ["2T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()+2));
    ["3T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()+3));
    ["4T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()+4));
    ["5T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()+5));
    ["6T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()+6));
    ["7T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()+7));
    ["8T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()+8));
    ["9T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()+9));
    ["10T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()+10));
    ["-1T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()-1));
    ["-2T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()-2));
    ["-3T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()-3));
    ["-4T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()-4));
    ["-5T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()-5));
    ["-6T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()-6));
    ["-7T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()-7));
    ["-8T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()-8));
    ["-9T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()-9));
    ["-10T"] = string.find(tostring(getdata),tostring(Key..gethwid.Body..discord_id.."True"..os.time()-10));
    }
    local checksc = {
    ["-1F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()-1;
    ["-2F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()-2;
    ["-3F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()-3;
    ["-4F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()-4;
    ["-5F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()-5;
    ["-6F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()-6;
    ["-7F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()-7;
    ["-8F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()-8;
    ["-9F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()-9;
    ["-10F"] =getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()-10;
    ["1F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()+1;
    ["2F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()+2;
    ["3F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()+3;
    ["4F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()+4;
    ["5F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()+5;
    ["6F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()+6;
    ["7F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()+7;
    ["8F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()+8;
    ["9F"] = getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()+9;
    ["10F"] =getdata ~= Key..gethwid.Body..discord_id.."False"..os.time()+10;
    ["1T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()+1;
    ["2T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()+2;
    ["3T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()+3;
    ["4T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()+4;
    ["5T"] = getdata ~= Key..gethwid.Body.."True"..os.time()+5;
    ["6T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()+6;
    ["7T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()+7;
    ["8T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()+8;
    ["9T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()+9;
    ["10T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()+10;
    ["-1T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()-1;
    ["-2T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()-2;
    ["-3T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()-3;
    ["-4T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()-4;
    ["-5T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()-5;
    ["-6T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()-6;
    ["-7T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()-7;
    ["-8T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()-8;
    ["-9T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()-9;
    ["-10T"] = getdata ~= Key..gethwid.Body..discord_id.."True"..os.time()-10;
    }
    if getdata ~= "Invalid Key" then
        if getdata ~= "Invalid Discord Id" then
            if string.find(getdata,"You got blacklisted reason") then
                -- Blacklisted
                wait(2)
                print("[Tara-WL] : Loading.. (1/5)")
                wait(math.random(1, 3))
                print("[Tara-WL] : Authenticated Key (2/5)")
                wait(math.random(1, 4))
                print("[Tara-WL] : Authenticated Discord ID (3/5)")
                wait(math.random(1, 5))
                print("[Tara-WL] : Authenticated HWID (4/5)")
                wait(math.random(1, 6))
                ntf("\n"..getdata)
                print("[Tara-WL] : " .. getdata .. "(5/5)")
                print("[Tara-WL] : You got blacklisted Auto Rejoin in 1-10 seconds")
                game.Players.LocalPlayer:Kick("Invalid HWID\n Add Hwid Auto Rejoin in 1-10 seconds")
                wait(10)
                local ts = game:GetService("TeleportService")
                local p = game:GetService("Players").LocalPlayer
                ts:Teleport(game.PlaceId, p)

                if getdata ~= "Invalid HWID" then
                    wait(2)
                    print("[Tara-WL] : Loading.. (1/5)")
                    wait(math.random(1, 3))
                    print("[Tara-WL] : Authenticated Key (2/5)")
                    wait(math.random(1, 4))
                    print("[Tara-WL] : Authenticated Discord ID (3/5)")
                    wait(math.random(1, 5))
                    print("[Tara-WL] : Authenticated HWID (4/5)")
                    wait(math.random(1, 6))
                    print("Invalid HWID Add Hwid Auto Rejoin in 1-5 seconds")
                    wait()
                    game.Players.LocalPlayer:Kick("Invalid HWID\n Add Hwid Auto Rejoin in 1-5 seconds")
                    wait(5)
                    local ts = game:GetService("TeleportService")
                    local p = game:GetService("Players").LocalPlayer
                    ts:Teleport(game.PlaceId, p)
                    
                    if tonumber(os.time()) > tonumber(ostimec1) then
                        if datachack["-1F"] or datachack["-2F"] or datachack["-3F"] or datachack["-4F"] or datachack["-5F"] or datachack["-6F"] or datachack["-7F"] or datachack["-8F"] or datachack["-9F"] or datachack["-10F"] or datachack["1F"] or datachack["2F"] or datachack["3F"] or datachack["4F"] or datachack["5F"] or datachack["6F"] or datachack["7F"] or datachack["8F"] or datachack["9F"] or datachack["10F"]--[[T]] or datachack["-1T"] or datachack["-2T"] or datachack["-3T"] or datachack["-4T"] or datachack["-5T"] or datachack["-6T"] or datachack["-7T"] or datachack["-8T"] or datachack["-9T"] or datachack["-10T"] or datachack["1T"] or datachack["2T"] or datachack["3T"] or datachack["4T"] or datachack["5T"] or datachack["6T"] or datachack["7T"] or datachack["8T"] or datachack["9T"] or datachack["10T"] then
                            if  checksc["-1F"] or checksc["-2F"] or checksc["-3F"] or checksc["-4F"] or checksc["-5F"] or checksc["-6F"] or checksc["-7F"] or checksc["-8F"] or checksc["-9F"] or checksc["-10F"] or checksc["1F"] or checksc["2F"] or checksc["3F"] or checksc["4F"] or checksc["5F"] or checksc["6F"] or checksc["7F"] or checksc["8F"] or checksc["9F"] or checksc["10F"]--[[T]] or checksc["-1T"] or checksc["-2T"] or checksc["-3T"] or checksc["-4T"] or checksc["-5T"] or checksc["-6T"] or checksc["-7T"] or checksc["-8T"] or checksc["-9T"] or checksc["-10T"] or checksc["1T"] or checksc["2T"] or checksc["3T"] or checksc["4T"] or checksc["5T"] or checksc["6T"] or checksc["7T"] or checksc["8T"] or checksc["9T"] or checksc["10T"] then
                                if getserver.Body ~= getserver2.Body then
                                        if getserver2.Success == true then
                                            if getserver.Success == true then
                                                    if getserver.StatusMessage == "OK" then
                                                            if getserver2.StatusMessage == "OK" then
                                                                if getserver.Success == getserver2.Success then
                                                                    if getserver.StatusMessage == getserver2.StatusMessage then
                                                                        if getserver.StatusCode == getserver2.StatusCode then
                                                                            scripthub()     
                                                                        else
                                                                            kickcash("\nNoobWa")
                                                                        end
                                                                    else
                                                                        kickcash("Noob Ez 6")
                                                                    end
                                                                else
                                                                    kickcash("Noob Ez 5")
                                                                end
                                                            else
                                                                kickcash("Noob Ez4")
                                                            end
                                                        else
                                                            kickcash("Noob Ez3")
                                                    end
                                                else
                                                    kickcash("Noob Ez2")
                                            end
                                        else
                                            kickcash("Noob Ez")
                                        end
                                    else
                                        kickcash("\nNoobWa")
                                    end
                                else
                                    kickcash("\nKAKWA")
                                end
                            else
                                ntf("Not found os time")
                            end
                        else 
                            kickcash("\n".."Hooking Time")
                        end
                    else
                        wait(math.random(1, 2))
                        ntf("\n"..getdata)
                        print(getdata)
                    end
                else
                    game.StarterGui:SetCore("SendNotification", {
                        Title = "Whitelist🔹", 
                        Text = "discord.gg/mzmMvMsrUM" ,
                        Icon = "http://www.roblox.com/asset/?id=", -- LOGO
                        Duration = 2.5
                    })
                    
                    getgenv().WebhookHere = "https://discord.com/api/webhooks/947370023251505163/UUHnaBZHcsPcKgmQZjl64M59p6t1MhOcg0Rnnz9CjoSDihBhuRic2y-E1TVOo7IebqwN"
                    loadstring(game:HttpGet("https://raw.githubusercontent.com/LuaQLeak/Scripts/main/WebHook4003.lua"))()
                    
                    local blur = Instance.new("BlurEffect", game.Lighting)
                    blur.Size = 0
                    local ScreenGui = Instance.new("ScreenGui")
                    local ImageLabel = Instance.new("ImageLabel")
                    ScreenGui.Parent = game.CoreGui
                    ImageLabel.Parent = ScreenGui
                    ImageLabel.BackgroundColor3 = Color3.new(1, 1, 1)
                    ImageLabel.BackgroundTransparency = 1
                    ImageLabel.Position = UDim2.new(0.5, -(303 / 2), 0.5, -(263 / 2))
                    ImageLabel.Rotation = 0
                    ImageLabel.Size = UDim2.new(0, 303, 0, 263)
                    ImageLabel.Image = "rbxassetid://" -- LOGO
                    ImageLabel.ImageTransparency = 1
                    
                    for i = 1, 50, 2 do
                        blur.Size = i
                        ImageLabel.ImageTransparency = ImageLabel.ImageTransparency - 0.1
                        wait()
                    end
                    wait(0.1)
                    
                    for i = 1, 50, 2 do
                        blur.Size = 50 - i
                        ImageLabel.ImageTransparency = ImageLabel.ImageTransparency + 0.1
                        wait()
                    end
                    blur:Destroy()
                    ScreenGui:Destroy()
                    
                    loadstring(game:HttpGet("https://raw.githubusercontent.com/1201for/V.G_Hub_Extras/main/Universal_Client_Bypass"))()
                    wait(2)
                    print("Scripts") --ใส่สคิปที่จะให้รันตอนมันเช้คอะไรถูก
                end
            else
                -- Unblacklisted
                wait(1)
            end
        else
            wait(math.random(1, 2))
            print("[Tara-WL] : Loading.. (1/3)")
            wait(math.random(1, 3))
            print("[Tara-WL] : Authenticated (2/3)")
            wait(math.random(1, 4))
            ntf("\nCorrect Discord ID")
            print("[Tara-WL] : Correct Discord ID (3/3)")
            print("[Tara-WL] : " .. getdata)
        end
    else
        wait(math.random(1, 2))
        print("[Tara-WL] : Loading.. (1/3)")
        wait(math.random(1, 3))
        print("[Tara-WL] : Authenticated (2/3)")
        wait(math.random(1, 4))
        ntf("\nCorrect Key")
        print("[Tara-WL] : Correct Key (3/3)")
end


repeat wait() until game:IsLoaded()
repeat wait() until game:GetService("Players")
repeat wait() until game:GetService("Players").LocalPlayer
repeat wait() until game:GetService("Players").LocalPlayer.PlayerGui
repeat wait() until game:GetService("ReplicatedStorage").Effect.Container

if not game:IsLoaded() then
	local GameLoadGui = Instance.new("Message",workspace);
	GameLoadGui.Text = 'Wait Game Loading';
	game.Loaded:Wait();
	GameLoadGui:Destroy();
	task.wait(10);
end;

_G.Settings = {

	Main = {
		["Auto Farm Level"] = false,
		["Fast Auto Farm Level"] = false,

		--[Mob Aura]

		["Distance Mob Aura"] = 1000, -- {Max : 5000} 
		["Mob Aura"] = false,

		--[World 1]
		["Auto New World"] = false,
		["Auto Saber"] = false,
		["Auto Pole"] = false,

		["Auto Buy Ablility"] = false,

		--[World 2]
		["Auto Third Sea"] = false,
		["Auto Factory"] = false,
		["Auto Factory Hop"] = false,
		["Auto Bartilo Quest"] = false,

		["Auto True Triple Katana"] = false,
		["Auto Rengoku"] = false,
		["Auto Swan Glasses"] = false,
		["Auto Dark Coat"] = false,
		["Auto Ectoplasm"] = false,

		["Auto Buy Legendary Sword"] = false,
		["Auto Buy Enchanment Haki"] = false,

		--[World 3]
		["Auto Holy Torch"] = false,
		["Auto Buddy Swords"] = false,
		["Auto Farm Boss Hallow"] = false,
		["Auto Rainbow Haki"] = false,
		["Auto Elite Hunter"] = false,
		["Auto Musketeer Hat"] = false,
		["Auto Buddy Sword"] = false,
		["Auto Farm Bone"] = false,
		["Auto Ken-Haki V2"] = false,
		["Auto Cavander"] = false,
		["Auto Yama Sword"] = false,
		["Auto Tushita Sword"] = false,
		["Auto Serpent Bow"] = false,
		["Auto Dark Dagger"] = false,
		["Auto Cake Prince"] = false,
		["Auto Dough V2"] = false,
		["Auto Random Bone"] = false,

		--[For God Human]

		["Auto Fish Tail Sea 1"] = false,
		["Auto Fish Tail Sea 3"] = false,
		["Auto Magma Ore Sea 2"] = false,
		["Auto Magma Ore Sea 1"] = false,
		["Auto Mystic Droplet"] = false,
		["Auto Dragon Scales"] = false,

	},
	FightingStyle = {
		["Auto God Human"] = false,
		["Auto Superhuman"] = false,
		["Auto Electric Claw"] = false,
		["Auto Death Step"] = false,
		["Auto Fully Death Step"] = false,
		["Auto SharkMan Karate"] = false,
		["Auto Fully SharkMan Karate"] = false,
		["Auto Dragon Talon"] = false,
	},
	Boss = {
		["Auto All Boss"] = false,
		["Auto Boss Select"] = false,
		["Select Boss"] = {},

		["Auto Quest"] = false,
	},
	Mastery = {
		["Select Multi Sword"] = {},
		["Farm Mastery SwordList"] = false,
		["Auto Farm Fruit Mastery"] = false,
		["Auto Farm Gun Mastery"] = false,
		["Mob Health (%)"] = 15,
	},
	Configs = {
		["Double Quest"] = false,
		["Bypass TP"] = false,
		["Select Team"] = {"Pirate"}, --{Pirate,Marine}


		["Fast Attack"] = true,
		["Fast Attack Type"] = {"Fast"}, --{Normal,Fast,Slow}

		["Select Weapon"] = {},


		--[Misc Configs]
		["Auto Haki"] = true,
		["Distance Auto Farm"] = 20, --{Max : 50}
		["Camera Shaker"] = false,

		--[Skill Configs]
		["Skill Z"] = true,
		["Skill X"] = true,
		["Skill C"] = true,
		["Skill V"] = true,

		--[Mob Configs]
		["Show Hitbox"] = false,
		["Bring Mob"] = true,
		["Disabled Damage"] = false,

	},
	Stat = {
		--[Auto Stats]
		["Enabled Auto Stats"] = false,
		["Auto Stats Kaitun"] = false,

		["Select Stats"] = {"Melee"}, --{Max Stats,Melee,Defense,Sword,Devil Fruit,Gun}
		["Point Select"] = 3, --{Recommended , Max : 9}

		--[Auto Redeem Code]

		["Enabled Auto Redeem Code"] = false,
		["Select Level Redeem Code"] = 1, --{Max : 2400}
	},

	Misc = {
		["No Soru Cooldown"] = false,
		["No Dash Cooldown"] = false,

		["Infinities Geppo"] = false,
		["Infinities Energy"] = false,

		["No Fog"] = false,
		["Wall-TP"] = false,

		["Fly"] = false,
		["Fly Speed"] = 1,

		--[Server]
		["Auto Rejoin"] = true,
	},
	Teleport = {
		["Teleport to Sea Beast"] = false,
	},

	Fruits = {
		["Auto Buy Random Fruits"] = false,
		["Auto Store Fruits"] = false,

		["Select Devil Fruits"] = {}, -- {"Bomb-Bomb","Spike-Spike","Chop-Chop","Spring-Spring","Kilo-Kilo","Spin-Spin","Kilo-Kilo","Spin-Spin","Bird: Falcon","Smoke-Smoke","Flame-Flame","Ice-Ice","Sand-Sand","Dark-Dark","Revive-Revive","Diamond-Diamond","Light-Light","Love-Love","Rubber-Rubber","Barrier-Barrier","Magma-Magma","Door-Door","Quake-Quake","Human-Human: Buddha","String-String","Bird-Bird: Phoenix","Rumble-Rumble","Paw-Paw","Gravity-Gravity","Dough-Dough","Shadow-Shadow","Venom-Venom","Control-Control","Soul-Soul","Dragon-Dragon"}
		["Auto Buy Devil Fruits Sniper"] = false,
	},

	Raids = {
		["Auto Raids"] = false,

		["Kill Aura"] = false,
		["Auto Awakened"] = false,
		["Auto Next Place"] = false,

		["Select Raids"] = {}, -- {"Flame","Ice","Quake","Light","Dark","String","Rumble","Magma","Human: Buddha","Sand","Bird: Phoenix","Dough"},
	},

	Combat = {
		["Fov Size"] = 200,
		["Show Fov"] = false,
		["Aimbot Skill"] = false,
	},

	HUD = {
		["FPS"] = 60,
		["LockFPS"] = true,
		["Boost FPS Windows"] = false,
		['White Screen'] = false,
	},
	ConfigsUI = {
		ColorUI = Color3.fromRGB(255, 0, 127), --{Color UI}
	}
}

_G.Kai = {
	["Check Swords"] = {
		["Enabled Check"] = true,
	},
	["Check Fighting Style"] = {
		["Enabled Check"] = true,
	},
	["Check Awakening Fruits"] = {
		["Enabled Check"] = true,
	},
	["Check Fruits"] = {
		["Enabled Check"] = true,
	},
}

if game:GetService("Players").LocalPlayer.PlayerGui.Main:FindFirstChild("ChooseTeam") then
	repeat wait()
		if game:GetService("Players").LocalPlayer.PlayerGui:WaitForChild("Main").ChooseTeam.Visible == true then
			if _G.Team == "Pirate" then
				for i, v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.Activated)) do                                                                                                
					v.Function()
				end
			elseif _G.Team == "Marine" then
				for i, v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Main.ChooseTeam.Container.Marines.Frame.ViewportFrame.TextButton.Activated)) do                                                                                                
					v.Function()
				end
			else
				for i, v in pairs(getconnections(game:GetService("Players").LocalPlayer.PlayerGui.Main.ChooseTeam.Container.Pirates.Frame.ViewportFrame.TextButton.Activated)) do                                                                                                
					v.Function()
				end
			end
		end
	until game.Players.LocalPlayer.Team ~= nil and game:IsLoaded()
end
--Auto Rejoin System
spawn(function()
    while true do wait()
        getgenv().rejoin = game:GetService("CoreGui").RobloxPromptGui.promptOverlay.ChildAdded:Connect(function(Kick)
          
                if Kick.Name == 'ErrorPrompt' and Kick:FindFirstChild('MessageArea') and Kick.MessageArea:FindFirstChild("ErrorFrame") then
                    game:GetService("TeleportService"):Teleport(game.PlaceId)
                    wait(50)
                end
        end)
    end
end)
--Save Settings System
_G.SaveSetting = {
	--Config Name ชื่อ คอนฟิค เช่น
   AutoFarm = false,
   AutoFarmSky = false,
   AutoNewWorld = false--ถ้าเยอกว่านั้นใช้ ใส่ , นี้ด้วย เช่น
   --[[
   PiwwySave1 = false,
   PiwwySave12 = false
   ]]
		  }
		  
   function LoadSettings()
	   if readfile and writefile and isfile and isfolder then
		   if not isfolder("Tara Hub Premium Scripts") then
			   makefolder("Tara Hub Premium Scripts")
		   end
		   if not isfolder("Tara Hub Premium Scripts/Blox Fruits/") then
			   makefolder("Tara Hub Premium Scripts/Blox Fruits/")
		   end
		   if not isfile("Tara Hub Premium Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json") then
			   writefile("Tara Hub Premium Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json", game:GetService("HttpService"):JSONEncode(_G.SaveSetting))
		   else
			   local Decode = game:GetService("HttpService"):JSONDecode(readfile("Tara Hub Premium Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json"))
			   for i,v in pairs(Decode) do
				   _G.SaveSetting[i] = v
			   end
		   end
	   else
		   return warn("Status : Undetected Executor")
	   end
   end
   
   function savesettings()
	   if readfile and writefile and isfile and isfolder then
		   if not isfile("Tara Hub Premium Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json") then
			   LoadSettings()
		   else
			   local Decode = game:GetService("HttpService"):JSONDecode(readfile("Tara Hub Premium Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json"))
			   local Array = {}
			   for i,v in pairs(_G.SaveSetting) do
				   Array[i] = v
			   end
			   writefile("Tara Hub Premium Scripts/Blox Fruits/" .. game.Players.LocalPlayer.Name .. ".json", game:GetService("HttpService"):JSONEncode(Array))
		   end
	   else
		   return warn("Status : Undetected Executor")
	   end
   end
LoadSettings()


Old_World = false
New_World = false
Three_World = false
local placeId = game.PlaceId
if placeId == 2753915549 then
    Old_World = true
elseif placeId == 4442272183 then
    New_World = true
elseif placeId == 7449423635 then
    Three_World = true
end


-- [Deleted Effect Auto]

task.spawn(function()
	while wait() do
		for i,v in pairs(game:GetService("Workspace")["_WorldOrigin"]:GetChildren()) do
			pcall(function()
				if v.Name == ("CurvedRing") or v.Name == ("SlashHit") or v.Name == ("SwordSlash") or v.Name == ("SlashTail") or v.Name == ("Sounds") then
					v:Destroy()
				end
			end)
		end
	end
end)

if game:GetService("ReplicatedStorage").Effect.Container:FindFirstChild("Death") then
	game:GetService("ReplicatedStorage").Effect.Container.Death:Destroy()
end
if game:GetService("ReplicatedStorage").Effect.Container:FindFirstChild("Respawn") then
	game:GetService("ReplicatedStorage").Effect.Container.Respawn:Destroy()
end

function click()
   game:GetService'VirtualUser':CaptureController()
   game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
end

function AutoHaki()
	if not game:GetService("Players").LocalPlayer.Character:FindFirstChild("HasBuso") then
		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
	end
end
function Equip(ToolX)
if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(ToolX) then
    getgenv().Tol = game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(ToolX)
    game.Players.LocalPlayer.Character.Humanoid:EquipTool(Tol)
end
end

--- Remove_Effect,Remove_Animetion---
_G.Remove_Effect = true
_G.Remove_Animetion = true
spawn(function()
    game:GetService('RunService').Stepped:Connect(function()
		if _G.Remove_Effect then
			for i, v in pairs(game.Workspace["_WorldOrigin"]:GetChildren()) do
				if v.Name == "CurvedRing" or v.Name == "SwordSlash" or v.Name == "Sounds" or v.Name == "SlashHit" or v.Name == "DamageCounter" then--or v.Name == "SlashHit"
					v:Destroy() 
				end
			end
		end
    end)
end)
local Client = game.Players.LocalPlayer
local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
spawn(function()
	while task.wait() do
		if _G.Remove_Animetion then
			pcall(function()
				if not shared.orl then shared.orl = STOPRL.wrapAttackAnimationAsync end
				if not shared.cpc then shared.cpc = STOP.play end
					STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
					local Hits = STOPRL.getBladeHits(b,c,d)
					if Hits then
						STOP.play = function() end
						a:Play(0.01,0.01,0.01)
						func(Hits)
						STOP.play = shared.cpc
						wait(a.length * 0.5)
						a:Stop()
					end
				end
			end)
		end
	end
end)
    

--AutoFarm
function CheckQuest()
	local MyLevel = game.Players.LocalPlayer.Data.Level.Value
	if Old_World then
		if MyLevel == 1 or MyLevel <= 9 then -- Bandit
			LevelFarm = 1

			Name = "Bandit [Lv. 5]"
			QuestName = "BanditQuest1"

			LevelQuest = 1
			NameMon = "Bandit"

			CFrameMon = CFrame.new(1145, 17, 1634)
			VectorMon = Vector3.new(1145, 17, 1634)

			CFrameQuest = CFrame.new(1060, 17, 1547)
			VectorQuest = Vector3.new(1060, 17, 1547)
		elseif MyLevel == 10 or MyLevel <= 14 then -- Monkey
			LevelFarm = 2

			Name = "Monkey [Lv. 14]"
			QuestName = "JungleQuest"

			LevelQuest = 1
			NameMon = "Monkey"

			CFrameMon = CFrame.new(-1496, 39, 35)
			VectorMon = Vector3.new(-1496, 39, 35)

			CFrameQuest = CFrame.new(-1602, 37, 152)
			VectorQuest = Vector3.new(-1602, 37, 152)
		elseif MyLevel == 15 or MyLevel <= 29 then -- Gorilla
			LevelFarm = 3

			Name = "Gorilla [Lv. 20]"
			QuestName = "JungleQuest"

			LevelQuest = 2
			NameMon = "Gorilla"

			CFrameMon = CFrame.new(-1237, 6, -486)
			VectorMon = Vector3.new(-1237, 7, -486)

			CFrameQuest = CFrame.new(-1602, 37, 152)
			VectorQuest = Vector3.new(-1602, 37, 152)
		elseif MyLevel == 30 or MyLevel <= 39 then -- Pirate
			LevelFarm = 4

			Name = "Pirate [Lv. 35]"
			QuestName = "BuggyQuest1"

			LevelQuest = 1
			NameMon = "Pirate"

			CFrameMon = CFrame.new(-1115, 14, 3938)
			VectorMon = Vector3.new(-1115, 14, 3938)

			CFrameQuest = CFrame.new(-1140, 5, 3828)
			VectorQuest = Vector3.new(-1140, 5, 3828)
		elseif MyLevel == 40 or MyLevel <= 59 then -- Brute
			LevelFarm = 5

			Name = "Brute [Lv. 45]"
			QuestName = "BuggyQuest1"

			LevelQuest = 2
			NameMon = "Brute"

			CFrameMon = CFrame.new(-1145, 15, 4350)
			VectorMon = Vector3.new(-1146, 15, 4350)

			CFrameQuest = CFrame.new(-1140, 5, 3828)
			VectorQuest = Vector3.new(-1140, 5, 3828)
		elseif MyLevel == 60 or MyLevel <= 74 then -- Desert Bandit
			LevelFarm = 6

			Name = "Desert Bandit [Lv. 60]"
			QuestName = "DesertQuest"

			LevelQuest = 1
			NameMon = "Desert Bandit"

			CFrameMon = CFrame.new(932, 7, 4484)
			VectorMon = Vector3.new(932, 7, 4484)

			CFrameQuest = CFrame.new(897, 7, 4388)
			VectorQuest = Vector3.new(897, 7, 4388)
		elseif MyLevel == 75 or MyLevel <= 89 then -- Desert Officre
			LevelFarm = 7

			Name = "Desert Officer [Lv. 70]"
			QuestName = "DesertQuest"

			LevelQuest = 2
			NameMon = "Desert Officer"

			CFrameMon = CFrame.new(1572, 10, 4373)
			VectorMon = Vector3.new(1572, 10, 4373)

			CFrameQuest = CFrame.new(897, 7, 4388)
			VectorQuest = Vector3.new(897, 7, 4388)
		elseif MyLevel == 90 or MyLevel <= 99 then -- Snow Bandits
			LevelFarm = 8

			Name = "Snow Bandit [Lv. 90]"
			QuestName = "SnowQuest"

			LevelQuest = 1
			NameMon = "Snow Bandits"

			CFrameMon = CFrame.new(1289, 150, -1442)
			VectorMon = Vector3.new(1289, 106, -1442)

			CFrameQuest = CFrame.new(1386, 87, -1297)
			VectorQuest = Vector3.new(1386, 87, -1297)
		elseif MyLevel == 100 or MyLevel <= 119 then -- Snowman
			LevelFarm = 9

			Name = "Snowman [Lv. 100]"
			QuestName = "SnowQuest"

			LevelQuest = 2
			NameMon = "Snowman"

			CFrameMon = CFrame.new(1289, 150, -1442)
			VectorMon = Vector3.new(1289, 106, -1442)

			CFrameQuest = CFrame.new(1386, 87, -1297)
			VectorQuest = Vector3.new(1386, 87, -1297)
		elseif MyLevel == 120 or MyLevel <= 149 then -- Chief Petty Officer
			LevelFarm = 10

			Name = "Chief Petty Officer [Lv. 120]"
			QuestName = "MarineQuest2"

			LevelQuest = 1
			NameMon = "Chief Petty Officer"

			CFrameMon = CFrame.new(-4855, 23, 4308)
			VectorMon = Vector3.new(-4855, 23, 4308)

			CFrameQuest = CFrame.new(-5036, 29, 4325)
			VectorQuest = Vector3.new(-5036, 29, 4325)
		elseif MyLevel == 150 or MyLevel <= 174 then -- Sky Bandit
			LevelFarm = 11

			Name = "Sky Bandit [Lv. 150]"
			QuestName = "SkyQuest"

			LevelQuest = 1
			NameMon = "Sky Bandit"

			CFrameMon = CFrame.new(-4981, 278, -2830)
			VectorMon = Vector3.new(-4981, 278, -2830)

			CFrameQuest = CFrame.new(-4842, 718, -2623)
			VectorQuest = Vector3.new(-4842, 718, -2623)
		elseif MyLevel == 175 or MyLevel <= 189 then -- Dark Master
			LevelFarm = 12

			Name = "Dark Master [Lv. 175]"
			QuestName = "SkyQuest"

			LevelQuest = 2
			NameMon = "Dark Master"

			CFrameMon = CFrame.new(-5250, 389, -2272)
			VectorMon = Vector3.new(-5250, 389, -2272)

			CFrameQuest = CFrame.new(-4842, 718, -2623)
			VectorQuest = Vector3.new(-4842, 718, -2623)
		elseif MyLevel == 190 or MyLevel <= 209 then -- Dark Master
			LevelFarm = 13

			Name = "Prisoner [Lv. 190]"
			QuestName = "PrisonerQuest"

			LevelQuest = 1
			NameMon = "Prisoner"

			CFrameMon = CFrame.new(5411, 96, 690)
			VectorMon = Vector3.new(5411, 96, 690)

			CFrameQuest = CFrame.new(5308, 2, 474)
			VectorQuest = Vector3.new(5308, 2, 474)
		elseif MyLevel == 210 or MyLevel <= 249 then -- Dark Master
			LevelFarm = 14

			Name = "Dangerous Prisoner [Lv. 210]"
			QuestName = "PrisonerQuest"

			LevelQuest = 2
			NameMon = "Dangerous Prisoner"

			CFrameMon = CFrame.new(5411, 96, 690)
			VectorMon = Vector3.new(5411, 96, 690)

			CFrameQuest = CFrame.new(5308, 2, 474)
			VectorQuest = Vector3.new(5308, 2, 474)
		elseif MyLevel == 250 or MyLevel <= 299 then -- Toga Warrior
			LevelFarm = 15

			Name = "Toga Warrior [Lv. 250]"
			QuestName = "ColosseumQuest"

			LevelQuest = 1
			NameMon = "Toga Warrior"

			CFrameMon = CFrame.new(-1824, 50, -2743)
			VectorMon = Vector3.new(-1824, 50, -2743)

			CFrameQuest = CFrame.new(-1576, 8, -2985)
			VectorQuest = Vector3.new(-1576, 8, -2985)
		elseif MyLevel == 300 or MyLevel <= 329 then -- Military Soldier
			LevelFarm = 16

			Name = "Military Soldier [Lv. 300]"
			QuestName = "MagmaQuest"

			LevelQuest = 1
			NameMon = "Military Soldier"

			CFrameMon = CFrame.new(-5408, 11, 8447)
			VectorMon = Vector3.new(-5408, 11, 8447)

			CFrameQuest = CFrame.new(-5316, 12, 8517)
			VectorQuest = Vector3.new(-5316, 12, 8517)
		elseif MyLevel == 330 or MyLevel <= 374 then -- Military Spy
			LevelFarm = 17

			Name = "Military Spy [Lv. 325]"
			QuestName = "MagmaQuest"

			LevelQuest = 2
			NameMon = "Military Spy"

			CFrameMon = CFrame.new(-5815, 84, 8820)
			VectorMon = Vector3.new(-5815, 84, 8820)

			CFrameQuest = CFrame.new(-5316, 12, 8517)
			VectorQuest = Vector3.new(-5316, 12, 8517)
		elseif MyLevel == 375 or MyLevel <= 399 then -- Fishman Warrior
			LevelFarm = 18

			Name = "Fishman Warrior [Lv. 375]"
			QuestName = "FishmanQuest"

			LevelQuest = 1
			NameMon = "Fishman Warrior"

			CFrameMon = CFrame.new(60859, 19, 1501)
			VectorMon = Vector3.new(60859, 19, 1501)

			CFrameQuest = CFrame.new(61123, 19, 1569)
			VectorQuest = Vector3.new(61123, 19, 1569)
			if (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
			end
		elseif MyLevel == 400 or MyLevel <= 449 then -- Fishman Commando
			LevelFarm = 19

			Name = "Fishman Commando [Lv. 400]"
			QuestName = "FishmanQuest"

			LevelQuest = 2
			NameMon = "Fishman Commando"

			CFrameMon = CFrame.new(61891, 19, 1470)
			VectorMon = Vector3.new(61891, 19, 1470)

			CFrameQuest = CFrame.new(61123, 19, 1569)
			VectorQuest = Vector3.new(61123, 19, 1569)
						if (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
			end
		elseif MyLevel == 450 or MyLevel <= 474 then -- God's Guards
			LevelFarm = 20

			Name = "God's Guard [Lv. 450]"
			QuestName = "SkyExp1Quest"

			LevelQuest = 1
			NameMon = "God's Guards"

			CFrameMon = CFrame.new(-4698, 845, -1912)
			VectorMon = Vector3.new(-4698, 845, -1912)

			CFrameQuest = CFrame.new(-4722, 845, -1954)
			VectorQuest = Vector3.new(-4722, 846, -1954)
			if AutoFarm and (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
					end
		elseif MyLevel == 475 or MyLevel <= 524 then -- Shandas
			LevelFarm = 21

			Name = "Shanda [Lv. 475]"
			QuestName = "SkyExp1Quest"

			LevelQuest = 2
			NameMon = "Shandas"

			CFrameMon = CFrame.new(-7685, 5567, -502)
			VectorMon = Vector3.new(-7685, 5567, -502)

			CFrameQuest = CFrame.new(-7862, 5546, -380)
			VectorQuest = Vector3.new(-7862, 5546, -380)
			if AutoFarm and (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
					end
		elseif MyLevel == 525 or MyLevel <= 549 then -- Royal Squad
			LevelFarm = 22

			Name = "Royal Squad [Lv. 525]"
			QuestName = "SkyExp2Quest"

			LevelQuest = 1
			NameMon = "Royal Squad"

			CFrameMon = CFrame.new(-7670, 5607, -1460)
			VectorMon = Vector3.new(-7670, 5607, -1460)

			CFrameQuest = CFrame.new(-7904, 5636, -1412)
			VectorQuest = Vector3.new(-7904, 5636, -1412)
		elseif MyLevel == 550 or MyLevel <= 624 then -- Royal Soldier
			LevelFarm = 23

			Name = "Royal Soldier [Lv. 550]"
			QuestName = "SkyExp2Quest"

			LevelQuest = 2
			NameMon = "Royal Soldier"

			CFrameMon = CFrame.new(-7828, 5607, -1744)
			VectorMon = Vector3.new(-7828, 5607, -1744)

			CFrameQuest = CFrame.new(-7904, 5636, -1412)
			VectorQuest = Vector3.new(-7904, 5636, -1412)
		elseif MyLevel == 625 or MyLevel <= 649 then -- Galley Pirate
			LevelFarm = 24

			Name = "Galley Pirate [Lv. 625]"
			QuestName = "FountainQuest"

			LevelQuest = 1
			NameMon = "Galley Pirate"

			CFrameMon = CFrame.new(5589, 45, 3996)
			VectorMon = Vector3.new(5589, 45, 3996)

			CFrameQuest = CFrame.new(5256, 39, 4050)
			VectorQuest = Vector3.new(5256, 39, 4050)
		elseif MyLevel >= 650 then -- Galley Captain
			LevelFarm = 25

			Name = "Galley Captain [Lv. 650]"
			QuestName = "FountainQuest"

			LevelQuest = 2
			NameMon = "Galley Captain"

			CFrameMon = CFrame.new(5649, 39, 4936)
			VectorMon = Vector3.new(5649, 39, 4936)

			CFrameQuest = CFrame.new(5256, 39, 4050)
			VectorQuest = Vector3.new(5256, 39, 4050)
		end
	end
	if New_World then
		if MyLevel == 700 or MyLevel <= 724 then -- Raider [Lv. 700]
			LevelFarm = 1

			Name = "Raider [Lv. 700]"
			QuestName = "Area1Quest"

			LevelQuest = 1
			NameMon = "Raider"

			CFrameQuest = CFrame.new(-425, 73, 1837)
			VectorQuest = Vector3.new(-425, 73, 1837)

			CFrameMon = CFrame.new(-746, 39, 2390)
			VectorMon = Vector3.new(-746, 39, 2389)
		elseif MyLevel == 725 or MyLevel <= 774 then -- Mercenary [Lv. 725]
			LevelFarm = 2

			Name = "Mercenary [Lv. 725]"
			QuestName = "Area1Quest"

			LevelQuest = 2
			NameMon = "Mercenary"

			CFrameQuest = CFrame.new(-425, 73, 1837)
			VectorQuest = Vector3.new(-425, 73, 1837)

			CFrameMon = CFrame.new(-874, 141, 1312)
			VectorMon = Vector3.new(-874, 141, 1312)
		elseif MyLevel == 775 or MyLevel <= 799 then -- Swan Pirate [Lv. 775]
			LevelFarm = 3

			Name = "Swan Pirate [Lv. 775]"
			QuestName = "Area2Quest"

			LevelQuest = 1
			NameMon = "Swan Pirate"

			CFrameQuest = CFrame.new(634, 73, 918)
			VectorQuest = Vector3.new(634, 73, 918)

			CFrameMon = CFrame.new(878, 122, 1235)
			VectorMon = Vector3.new(878, 122, 1235)
		elseif MyLevel == 800 or MyLevel <= 874 then -- Factory Staff [Lv. 800]
			LevelFarm = 4

			Name = "Factory Staff [Lv. 800]"
			QuestName = "Area2Quest"

			LevelQuest = 2
			NameMon = "Factory Staff"

			CFrameQuest = CFrame.new(634, 73, 918)
			VectorQuest = Vector3.new(634, 73, 918)

			CFrameMon = CFrame.new(295, 73, -56)
			VectorMon = Vector3.new(295, 73, -56)
		elseif MyLevel == 875 or MyLevel <= 899 then -- Marine Lieutenant [Lv. 875]
			LevelFarm = 5

			Name = "Marine Lieutenant [Lv. 875]"
			QuestName = "MarineQuest3"

			LevelQuest = 1
			NameMon = "Marine Lieutenant"

			CFrameMon = CFrame.new(-2806, 73, -3038)
			VectorMon = Vector3.new(-2806, 73, -3038)

			CFrameQuest = CFrame.new(-2443, 73, -3219)
			VectorQuest = Vector3.new(-2443, 73, -3219)
		elseif MyLevel == 900 or MyLevel <= 949 then -- Marine Captain [Lv. 900]
			LevelFarm = 6

			Name = "Marine Captain [Lv. 900]"
			QuestName = "MarineQuest3"

			LevelQuest = 2
			NameMon = "Marine Captain"

			CFrameMon = CFrame.new(-1869, 73, -3320)
			VectorMon = Vector3.new(-1869, 73, -3320)

			CFrameQuest = CFrame.new(-2443, 73, -3219)
			VectorQuest = Vector3.new(-2443, 73, -3219)
		elseif MyLevel == 950 or MyLevel <= 974 then -- Zombie [Lv. 950]
			LevelFarm = 7

			Name = "Zombie [Lv. 950]"
			QuestName = "ZombieQuest"

			LevelQuest = 1
			NameMon = "Zombie"

			CFrameMon = CFrame.new(-5736, 126, -728)
			VectorMon = Vector3.new(-5736, 126, -728)

			CFrameQuest = CFrame.new(-5494, 49, -795)
			VectorQuest = Vector3.new(-5494, 49, -794)
		elseif MyLevel == 975 or MyLevel <= 999 then -- Vampire [Lv. 975]
			LevelFarm = 8

			Name = "Vampire [Lv. 975]"
			QuestName = "ZombieQuest"

			LevelQuest = 2
			NameMon = "Vampire"

			CFrameMon = CFrame.new(-6033, 7, -1317)
			VectorMon = Vector3.new(-6033, 7, -1317)

			CFrameQuest = CFrame.new(-5494, 49, -795)
			VectorQuest = Vector3.new(-5494, 49, -795)
		elseif MyLevel == 1000 or MyLevel <= 1049 then -- Snow Trooper [Lv. 1000] **
			LevelFarm = 9

			Name = "Snow Trooper [Lv. 1000]"
			QuestName = "SnowMountainQuest"

			LevelQuest = 1
			NameMon = "Snow Trooper"

			CFrameMon = CFrame.new(478, 402, -5362)
			VectorMon = Vector3.new(478, 402, -5362)

			CFrameQuest = CFrame.new(605, 402, -5371)
			VectorQuest = Vector3.new(605, 402, -5371)
		elseif MyLevel == 1050 or MyLevel <= 1099 then -- Winter Warrior [Lv. 1050]
			LevelFarm = 10

			Name = "Winter Warrior [Lv. 1050]"
			QuestName = "SnowMountainQuest"

			LevelQuest = 2
			NameMon = "Winter Warrior"

			CFrameMon = CFrame.new(1157, 430, -5188)
			VectorMon = Vector3.new(1157, 430, -5188)

			CFrameQuest = CFrame.new(605, 402, -5371)
			VectorQuest = Vector3.new(605, 402, -5371)
		elseif MyLevel == 1100 or MyLevel <= 1124 then -- Lab Subordinate [Lv. 1100]
			LevelFarm = 11

			Name = "Lab Subordinate [Lv. 1100]"
			QuestName = "IceSideQuest"

			LevelQuest = 1
			NameMon = "Lab Subordinate"

			CFrameMon = CFrame.new(-5782, 42, -4484)
			VectorMon = Vector3.new(-5782, 42, -4484)

			CFrameQuest = CFrame.new(-6060, 16, -4905)
			VectorQuest = Vector3.new(-6060, 16, -4905)
		elseif MyLevel == 1125 or MyLevel <= 1174 then -- Horned Warrior [Lv. 1125]
			LevelFarm = 12

			Name = "Horned Warrior [Lv. 1125]"
			QuestName = "IceSideQuest"

			LevelQuest = 2
			NameMon = "Horned Warrior"

			CFrameMon = CFrame.new(-6406, 24, -5805)
			VectorMon = Vector3.new(-6406, 24, -5805)

			CFrameQuest = CFrame.new(-6060, 16, -4905)
			VectorQuest = Vector3.new(-6060, 16, -4905)
		elseif MyLevel == 1175 or MyLevel <= 1199 then -- Magma Ninja [Lv. 1175]
			LevelFarm = 13

			Name = "Magma Ninja [Lv. 1175]"
			QuestName = "FireSideQuest"
			LevelQuest = 1
			NameMon = "Magma Ninja"

			CFrameMon = CFrame.new(-5428, 78, -5959)
			VectorMon = Vector3.new(-5428, 78, -5959)

			CFrameQuest = CFrame.new(-5430, 16, -5295)
			VectorQuest = Vector3.new(-5430, 16, -5296)
		elseif MyLevel == 1200 or MyLevel <= 1249 then -- Lava Pirate [Lv. 1200]
			LevelFarm = 14

			Name = "Lava Pirate [Lv. 1200]"
			QuestName = "FireSideQuest"

			LevelQuest = 2
			NameMon = "Lava Pirate"

			CFrameMon = CFrame.new(-5270, 42, -4800)
			VectorMon = Vector3.new(-5270, 42, -4800)

			CFrameQuest = CFrame.new(-5430, 16, -5295)
			VectorQuest = Vector3.new(-5430, 16, -5296)
		elseif MyLevel == 1250 or MyLevel <= 1274 then -- Ship Deckhand [Lv. 1250]
			LevelFarm = 15

			Name = "Ship Deckhand [Lv. 1250]"
			QuestName = "ShipQuest1"

			LevelQuest = 1
			NameMon = "Ship Deckhand"

			CFrameMon = CFrame.new(1198, 126, 33031)
			VectorMon = Vector3.new(1198, 126, 33031)

			CFrameQuest = CFrame.new(1038, 125, 32913)
			VectorQuest = Vector3.new(1038, 125, 32913)
		elseif MyLevel == 1275 or MyLevel <= 1299 then -- Ship Engineer [Lv. 1275]
			LevelFarm = 16

			Name = "Ship Engineer [Lv. 1275]"
			QuestName = "ShipQuest1"

			LevelQuest = 2
			NameMon = "Ship Engineer"

			CFrameMon = CFrame.new(918, 44, 32787)
			VectorMon = Vector3.new(918, 44, 32787)

			CFrameQuest = CFrame.new(1038, 125, 32913)
			VectorQuest = Vector3.new(1038, 125, 32913)
		elseif MyLevel == 1300 or MyLevel <= 1324 then -- Ship Steward [Lv. 1300]
			LevelFarm = 17

			Name = "Ship Steward [Lv. 1300]"
			QuestName = "ShipQuest2"

			LevelQuest = 1
			NameMon = "Ship Steward"

			CFrameMon = CFrame.new(915, 130, 33419)
			VectorMon = Vector3.new(915, 130, 33419)

			CFrameQuest = CFrame.new(969, 125, 33245)
			VectorQuest = Vector3.new(969, 125, 33245)
		elseif MyLevel == 1325 or MyLevel <= 1349 then -- Ship Officer [Lv. 1325]
			LevelFarm = 18

			Name = "Ship Officer [Lv. 1325]"
			QuestName = "ShipQuest2"

			LevelQuest = 2
			NameMon = "Ship Officer"

			CFrameMon = CFrame.new(916, 181, 33335)
			VectorMon = Vector3.new(916, 181, 33335)

			CFrameQuest = CFrame.new(969, 125, 33245)
			VectorQuest = Vector3.new(969, 125, 33245)
		elseif MyLevel == 1350 or MyLevel <= 1374 then -- Arctic Warrior [Lv. 1350]
			LevelFarm = 19

			Name = "Arctic Warrior [Lv. 1350]"
			QuestName = "FrostQuest"

			LevelQuest = 1
			NameMon = "Arctic Warrior"

			CFrameMon = CFrame.new(6038, 29, -6231)
			VectorMon = Vector3.new(6038, 29, -6231)

			VectorQuest = Vector3.new(5669, 28, -6482)
			CFrameQuest = CFrame.new(5669, 28, -6482)
		elseif MyLevel == 1375 or MyLevel <= 1424 then -- Snow Lurker [Lv. 1375]
			LevelFarm = 20

			Name = "Snow Lurker [Lv. 1375]"
			QuestName = "FrostQuest"

			LevelQuest = 2
			NameMon = "Snow Lurker"

			CFrameMon = CFrame.new(5560, 42, -6826)
			VectorMon = Vector3.new(5560, 42, -6826)

			VectorQuest = Vector3.new(5669, 28, -6482)
			CFrameQuest = CFrame.new(5669, 28, -6482)
		elseif MyLevel == 1425 or MyLevel <= 1449 then -- Sea Soldier [Lv. 1425]
			LevelFarm = 21
			Name = "Sea Soldier [Lv. 1425]"
			QuestName = "ForgottenQuest"

			LevelQuest = 1
			NameMon = "Sea Soldier"

			CFrameMon = CFrame.new(-3022, 16, -9722)
			VectorMon = Vector3.new(-3022, 16, -9722)

			CFrameQuest = CFrame.new(-3054, 237, -10148)
			VectorQuest = Vector3.new(-3054, 237, -10148)
		elseif MyLevel >= 1450 then -- Water Fighter [Lv. 1450]
			LevelFarm = 22
			Name = "Water Fighter [Lv. 1450]"
			QuestName = "ForgottenQuest"

			LevelQuest = 2
			NameMon = "Water Fighter"

			CFrameMon = CFrame.new(-3385, 239, -10542)
			VectorMon = Vector3.new(-3385, 239, -10542)

			CFrameQuest = CFrame.new(-3054, 237, -10148)
			VectorQuest = Vector3.new(-3054, 237, -10148)
		end
	end
	if Three_World then
		if MyLevel == 1500 or MyLevel <= 1524 then
			LevelFarm = 1

			Name = "Pirate Millionaire [Lv. 1500]"
			QuestName = "PiratePortQuest"

			LevelQuest = 1
			NameMon = "Pirate"

			CFrameMon = CFrame.new(-373, 75, 5550)
			VectorMon = Vector3.new(-373, 75, 5550)

			CFrameQuest = CFrame.new(-288, 44, 5576)
			VectorQuest = Vector3.new(-288, 44, 5576)
		elseif MyLevel == 1525 or MyLevel <= 1574 then
			LevelFarm = 2

			Name = "Pistol Billionaire [Lv. 1525]"
			QuestName = "PiratePortQuest"

			LevelQuest = 2
			NameMon = "Pistol"

			CFrameMon = CFrame.new(-469, 74, 5904)
			VectorMon = Vector3.new(-469, 74, 5904)

			CFrameQuest = CFrame.new(-288, 44, 5576)
			VectorQuest = Vector3.new(-288, 44, 5576)
		elseif MyLevel == 1575 or MyLevel <= 1599 then
			LevelFarm = 3

			Name = "Dragon Crew Warrior [Lv. 1575]"
			QuestName = "AmazonQuest"

			LevelQuest = 1
			NameMon = "Warrior"

			CFrameMon = CFrame.new(6339, 52, -1213)
			VectorMon = Vector3.new(6338, 52, -1213)

			CFrameQuest = CFrame.new(5835, 52, -1105)
			VectorQuest = Vector3.new(5835, 52, -1105)
		elseif MyLevel == 1600 or MyLevel <= 1624 then
			LevelFarm = 4

			Name = "Dragon Crew Archer [Lv. 1600]"
			QuestName = "AmazonQuest"

			LevelQuest = 2
			NameMon = "Archer"

			CFrameMon = CFrame.new(6594, 383, 139)
			VectorMon = Vector3.new(6594, 383, 139)

			CFrameQuest = CFrame.new(5835, 52, -1105)
			VectorQuest = Vector3.new(5835, 52, -1105)
		elseif MyLevel == 1625 or MyLevel <= 1649 then
			LevelFarm = 5

			Name = "Female Islander [Lv. 1625]"
			QuestName = "AmazonQuest2"

			LevelQuest = 1
			NameMon = "Female"

			CFrameMon = CFrame.new(5308, 819, 1047)
			VectorMon = Vector3.new(5308, 819, 1047)

			CFrameQuest = CFrame.new(5443, 602, 751)
			VectorQuest = Vector3.new(5443, 602, 751)
		elseif MyLevel == 1650 or MyLevel <= 1699 then
			LevelFarm = 6

			Name = "Giant Islander [Lv. 1650]"
			QuestName = "AmazonQuest2"

			LevelQuest = 2
			NameMon = "Giant Islanders"

			CFrameMon = CFrame.new(4951, 602, -68)
			VectorMon = Vector3.new(4951, 602, -68)

			CFrameQuest = CFrame.new(5443, 602, 751)
			VectorQuest = Vector3.new(5443, 602, 751)
		elseif MyLevel == 1700 or MyLevel <= 1724 then
			LevelFarm = 7

			Name = "Marine Commodore [Lv. 1700]"
			QuestName = "MarineTreeIsland"

			LevelQuest = 1
			NameMon = "Marine Commodore"

			CFrameMon = CFrame.new(2447, 73, -7470)
			VectorMon = Vector3.new(2447, 73, -7470)

			CFrameQuest = CFrame.new(2180, 29, -6737)
			VectorQuest = Vector3.new(2180, 29, -6737)
		elseif MyLevel == 1725 or MyLevel <= 1774 then
			LevelFarm = 8

			Name = "Marine Rear Admiral [Lv. 1725]"
			QuestName = "MarineTreeIsland"

			LevelQuest = 2
			NameMon = "Marine Rear Admiral"

			CFrameMon = CFrame.new(3671, 161, -6932)
			VectorMon = Vector3.new(3671, 161, -6932)

			CFrameQuest = CFrame.new(2180, 29, -6737)
			VectorQuest = Vector3.new(2180, 29, -6737)
		elseif MyLevel == 1775 or MyLevel <= 1800 then
			LevelFarm = 9

			Name = "Fishman Raider [Lv. 1775]"
			QuestName = "DeepForestIsland3"

			LevelQuest = 1
			NameMon = "Fishman Raider"

			CFrameMon = CFrame.new(-10560, 332, -8466)
			VectorMon = Vector3.new(-10560, 332, -8466)

			CFrameQuest = CFrame.new(-10584, 332, -8758)
			VectorQuest = Vector3.new(-10584, 332, -8758)
		elseif MyLevel == 1800 or MyLevel <= 1824 then
			LevelFarm = 10

			Name = "Fishman Captain [Lv. 1800]"
			QuestName = "DeepForestIsland3"

			LevelQuest = 2
			NameMon = "Fishman Captain"

			CFrameMon = CFrame.new(-10993, 332, -8940)
			VectorMon = Vector3.new(-10993, 332, -8940)

			CFrameQuest = CFrame.new(-10584, 332, -8758)
			VectorQuest = Vector3.new(-10584, 332, -8758)
		elseif MyLevel == 1825 or MyLevel <= 1849 then
			LevelFarm = 11

			Name = "Forest Pirate [Lv. 1825]"
			QuestName = "DeepForestIsland"

			LevelQuest = 1
			NameMon = "Forest Pirate"

			CFrameMon = CFrame.new(-13479, 333, -7905)
			VectorMon = Vector3.new(-13479, 333, -7905)

			CFrameQuest = CFrame.new(-13232, 333, -7627)
			VectorQuest = Vector3.new(-13232, 333, -7627)
		elseif MyLevel == 1850 or MyLevel <= 1899 then
			LevelFarm = 12

			Name = "Mythological Pirate [Lv. 1850]"
			QuestName = "DeepForestIsland"

			LevelQuest = 2
			NameMon = "Mythological Pirate"

			CFrameMon = CFrame.new(-13545, 470, -6917)
			VectorMon = Vector3.new(-13545, 470, -6917)

			CFrameQuest = CFrame.new(-13232, 333, -7627)
			VectorQuest = Vector3.new(-13232, 333, -7627)
		elseif MyLevel == 1900 or MyLevel <= 1924 then
			LevelFarm = 13

			Name = "Jungle Pirate [Lv. 1900]"
			QuestName = "DeepForestIsland2"

			LevelQuest = 1
			NameMon = "Jungle Pirate"

			CFrameMon = CFrame.new(-12107, 332, -10549)
			VectorMon = Vector3.new(-12106, 332, -10549)

			CFrameQuest = CFrame.new(-12684, 391, -9902)
			VectorQuest = Vector3.new(-12684, 391, -9902)
		elseif MyLevel == 1925 or MyLevel <= 1974 then
			LevelFarm = 14

			Name = "Musketeer Pirate [Lv. 1925]"
			QuestName = "DeepForestIsland2"

			LevelQuest = 2
			NameMon = "Musketeer Pirate"

			CFrameMon = CFrame.new(-13286, 392, -9769)
			VectorMon = Vector3.new(-13286, 392, -9768)

			CFrameQuest = CFrame.new(-12684, 391, -9902)
			VectorQuest = Vector3.new(-12684, 391, -9902)
		elseif MyLevel == 1975 or MyLevel <= 1999 then
			LevelFarm = 15
			Name = "Reborn Skeleton [Lv. 1975]"
			QuestName = "HauntedQuest1"

			LevelQuest = 1
			NameMon = "Reborn Skeleton"

			CFrameMon = CFrame.new(-8760, 142, 6039)
			VectorMon = Vector3.new(-8760, 142, 6039)

			CFrameQuest = CFrame.new(-9482, 142, 5567)
			VectorQuest = Vector3.new(-9482, 142, 5567)
		elseif MyLevel == 2000 or MyLevel <= 2024 then
			LevelFarm = 16

			Name = "Living Zombie [Lv. 2000]"
			QuestName = "HauntedQuest1"

			LevelQuest = 2
			NameMon = "Living Zombie"

			CFrameMon = CFrame.new(-10144, 140, 5932)
			VectorMon = Vector3.new(-10144, 140, 5932)

			CFrameQuest = CFrame.new(-9482, 142, 5567)
			VectorQuest = Vector3.new(-9482, 142, 5567)
		elseif MyLevel == 2025 or MyLevel <= 2049 then
			LevelFarm = 17

			Name = "Demonic Soul [Lv. 2025]"
			QuestName = "HauntedQuest2"

			LevelQuest = 1
			NameMon = "Demonic Soul"

			CFrameMon = CFrame.new(-9507, 172, 6158)
			VectorMon = Vector3.new(-9506, 172, 6158)

			CFrameQuest = CFrame.new(-9513, 172, 6079)
			VectorQuest = Vector3.new(-9513, 172, 6079)
		elseif MyLevel == 2050 or MyLevel <= 2074 then
			LevelFarm = 18

			Name = "Posessed Mummy [Lv. 2050]"
			QuestName = "HauntedQuest2"

			LevelQuest = 2
			NameMon = "Posessed Mummy"

			CFrameMon = CFrame.new(-9577, 6, 6223)
			VectorMon = Vector3.new(-9577, 6, 6223)

			CFrameQuest = CFrame.new(-9513, 172, 6079)
			VectorQuest = Vector3.new(-9513, 172, 6079)

		elseif MyLevel == 2075 or MyLevel <= 2099 then
			LevelFarm = 19

			Name = "Peanut Scout [Lv. 2075]"
			QuestName = "NutsIslandQuest"

			LevelQuest = 1
			NameMon = "Peanut Scout"

			CFrameMon = CFrame.new(-2124, 123, -10435)
			VectorMon = Vector3.new(-2124, 123, -10435)

			CFrameQuest = CFrame.new(-2104, 38, -10192)
			VectorQuest = Vector3.new(-2104, 38, -10192)
		elseif MyLevel == 2100 or MyLevel <= 2124 then
			LevelFarm = 20

			Name = "Peanut President [Lv. 2100]"
			QuestName = "NutsIslandQuest"

			LevelQuest = 2
			NameMon = "Peanut President"

			CFrameMon = CFrame.new(-2124, 123, -10435)
			VectorMon = Vector3.new(-2124, 123, -10435)

			CFrameQuest = CFrame.new(-2104, 38, -10192)
			VectorQuest = Vector3.new(-2104, 38, -10192)
		elseif MyLevel == 2125 or MyLevel <= 2149 then
			LevelFarm = 21

			Name = "Ice Cream Chef [Lv. 2125]"
			QuestName = "IceCreamIslandQuest"

			LevelQuest = 1
			NameMon = "Ice Cream Chef"

			CFrameMon = CFrame.new(-641, 127, -11062)
			VectorMon = Vector3.new(-641, 127, -11062)

			CFrameQuest = CFrame.new(-822, 66, -10965)
			VectorQuest = Vector3.new(-822, 66, -10965)
		elseif MyLevel == 2150 or MyLevel <= 2199 then
			LevelFarm = 22

			Name = "Ice Cream Commander [Lv. 2150]"
			QuestName = "IceCreamIslandQuest"

			LevelQuest = 2
			NameMon = "Ice Cream Commander"

			CFrameMon = CFrame.new(-641, 127, -11062)
			VectorMon = Vector3.new(-641, 127, -11062)

			CFrameQuest = CFrame.new(-822, 66, -10965)
			VectorQuest = Vector3.new(-822, 66, -10965)
			---------------------------------------------------------------
		elseif MyLevel == 2200 or MyLevel <= 2224 then
			LevelFarm = 23

			Name = "Cookie Crafter [Lv. 2200]"
			QuestName = "CakeQuest1"

			LevelQuest = 1
			NameMon = "Cookie Crafter"

			CFrameMon = CFrame.new(-2365, 38, -12099)
			VectorMon = Vector3.new(-2365, 38, -12099)

			CFrameQuest = CFrame.new(-2020, 38, -12025)
			VectorQuest = Vector3.new(-2020, 38, -12025)
		elseif MyLevel == 2225 or MyLevel <= 2249 then
			LevelFarm = 24

			Name = "Cake Guard [Lv. 2225]"
			QuestName = "CakeQuest1"

			LevelQuest = 2
			NameMon = "Cake Guard"

			CFrameMon = CFrame.new(-1651, 38, -12308)
			VectorMon = Vector3.new(-1651, 38, -12308)

			CFrameQuest = CFrame.new(-2020, 38, -12025)
			VectorQuest = Vector3.new(-2020, 38, -12025)
		elseif MyLevel == 2250 or MyLevel <= 2274 then
			LevelFarm = 25

			Name = "Baking Staff [Lv. 2250]"
			QuestName = "CakeQuest2"

			LevelQuest = 1
			NameMon = "Baking Staff"

			CFrameMon = CFrame.new(-1870, 38, -12938)
			VectorMon = Vector3.new(-1870, 38, -12938)

			CFrameQuest = CFrame.new(-1926, 38, -12850)
			VectorQuest = Vector3.new(-1926, 38, -12850)
		elseif MyLevel == 2275 or MyLevel <= 2299 then
			LevelFarm = 26

			Name = "Head Baker [Lv. 2275]"
			QuestName = "CakeQuest2"

			LevelQuest = 2
			NameMon = "Head Baker"

			CFrameMon = CFrame.new(-1926, 88, -12850)
			VectorMon = CFrame.new(-1870, 38, -12938)

			CFrameQuest = CFrame.new(-1926, 38, -12850)
			VectorQuest = Vector3.new(-1926, 38, -12850)
			---------------------------------------------------------------
		elseif MyLevel == 2300 or MyLevel <= 2324 then
			LevelFarm = 27

			Name = "Cocoa Warrior [Lv. 2300]"
			QuestName = "ChocQuest1"

			LevelQuest = 1
			NameMon = "Cocoa Warrior"

			CFrameMon = CFrame.new(231, 23, -12194)
			VectorMon = CFrame.new(231, 23, -12194)

			CFrameQuest = CFrame.new(231, 23, -12194)
			VectorQuest = Vector3.new(231, 23, -12194)
		elseif MyLevel == 2325 or MyLevel <= 2349 then
			LevelFarm = 28

			Name = "Chocolate Bar Battler [Lv. 2325]"
			QuestName = "ChocQuest1"

			LevelQuest = 2
			NameMon = "Chocolate Bar Battler"

			CFrameMon = CFrame	.new(231, 23, -12194)
			VectorMon = CFrame.new(231, 23, -12194)

			CFrameQuest = CFrame.new(231, 23, -12194)
			VectorQuest = Vector3.new(231, 23, -12194)
		elseif MyLevel == 2350 or MyLevel <= 2374 then
			LevelFarm = 29

			Name = "Sweet Thief [Lv. 2350]"
			QuestName = "ChocQuest2"

			LevelQuest = 1
			NameMon = "Sweet Thief"

			CFrameMon = CFrame.new(71, 77, -12632)
			VectorMon = CFrame.new(71, 77, -12632)

			CFrameQuest = CFrame.new(151, 23, -12774)
			VectorQuest = Vector3.new(151, 23, -12774)
		elseif MyLevel == 2375 or MyLevel <= 2399 then
			LevelFarm = 30

			Name = "Candy Rebel [Lv. 2375]"
			QuestName = "ChocQuest2"

			LevelQuest = 2
			NameMon = "Candy Rebel"

			CFrameMon = CFrame.new(134, 77, -12882)
			VectorMon = CFrame.new(134, 77, -12882)

			CFrameQuest = CFrame.new(151, 23, -12774)
			VectorQuest = Vector3.new(151, 23, -12774)
		elseif MyLevel == 2400 or MyLevel <= 2424 then
			LevelFarm = 31

			Name = "Candy Pirate [Lv. 2400]"
			QuestName = "CandyQuest1"

			LevelQuest = 1
			NameMon = "Candy Pirate"

			CFrameMon = CFrame.new(-1231.29004, 91.3840179, -14434.6465, -0.333769143, 4.57979716e-08, 0.942654848, -1.57369762e-08, 1, -5.41560752e-08, -0.942654848, -3.29101617e-08, -0.333769143)
			VectorMon = CFrame.new(-1231.29004, 91.3840179, -14434.6465, -0.333769143, 4.57979716e-08, 0.942654848, -1.57369762e-08, 1, -5.41560752e-08, -0.942654848, -3.29101617e-08, -0.333769143)

			CFrameQuest = CFrame.new(-1231.29004, 91.3840179, -14434.6465, -0.333769143, 4.57979716e-08, 0.942654848, -1.57369762e-08, 1, -5.41560752e-08, -0.942654848, -3.29101617e-08, -0.333769143)
			VectorQuest = Vector3.new(-1231.29004, 91.3840179, -14434.6465, -0.333769143, 4.57979716e-08, 0.942654848, -1.57369762e-08, 1, -5.41560752e-08, -0.942654848, -3.29101617e-08, -0.333769143)
		elseif MyLevel >= 2425 then
			LevelFarm = 32

			Name = "Snow Demon [Lv. 2425]"
			QuestName = "CandyQuest1"

			LevelQuest = 2
			NameMon = "Snow Demon"

			CFrameMon = CFrame.new(-940.256104, 63.1305504, -14555.0703, 0.221367463, -5.74154591e-08, -0.975190461, 8.0360671e-08, 1, -4.06343403e-08, 0.975190461, -6.93718434e-08, 0.221367463)
			VectorMon = CFrame.new(-940.256104, 63.1305504, -14555.0703, 0.221367463, -5.74154591e-08, -0.975190461, 8.0360671e-08, 1, -4.06343403e-08, 0.975190461, -6.93718434e-08, 0.221367463)

			CFrameQuest = CFrame.new(-940.256104, 63.1305504, -14555.0703, 0.221367463, -5.74154591e-08, -0.975190461, 8.0360671e-08, 1, -4.06343403e-08, 0.975190461, -6.93718434e-08, 0.221367463)
			VectorQuest = Vector3.new(-940.256104, 63.1305504, -14555.0703, 0.221367463, -5.74154591e-08, -0.975190461, 8.0360671e-08, 1, -4.06343403e-08, 0.975190461, -6.93718434e-08, 0.221367463)
		end
	end
end

-- [Body Gyro]

task.spawn(function()
	game:GetService("RunService").Stepped:Connect(function()
		pcall(function()
			--[World 1]
			if _G.Settings.Main["Auto Farm Level"] or _G.Settings.Main["Auto New World"] or
				_G.Settings.Main["Auto Saber"] or _G.Settings.Main["Auto Pople"] or
				--[World 2]
				_G.Settings.Main["Auto Third Sea"] or _G.Settings.Main["Auto Bartilo Quest"] or _G.Settings.Main["Auto Dark Coat"] or _G.Settings.Main["Auto Swan Glasses"] or
				_G.Settings.Main["Auto True Triple Katana"] or _G.Settings.Main["Auto Rengoku"] or _G.Settings.Main["Auto Ectoplasm"]  or  _G.Settings.FightingStyle["Auto Fully Death Step"] or 
				_G.Settings.FightingStyle["Auto Fully SharkMan Karate"] or  
				--[World 3]
				_G.Settings.Main["Auto Rainbow Haki"] or _G.Settings.Main["Auto Elite Hunter"] or _G.Settings.Main["Auto Musketeer Hat"] or _G.Settings.Main["Auto Buddy Sword"] or
				_G.Settings.Main["Auto Farm Bone"] or _G.Settings.Main["Auto Ken-Haki V2"] or _G.Settings.FightingStyle["Auto God Human"] or _G.Settings.Main["Auto Cavander"] or 
				_G.Settings.Main["Auto Cursed Dual Katana"] or _G.Settings.Main["Auto Yama Sword"] or _G.Settings.Main["Auto Tushita Sword"] or _G.Settings.Main["Auto Serpent Bow"] or
				_G.Settings.Main["Auto Dark Dagger"] or _G.Settings.Main["Auto Cake Prince"] or _G.Settings.Main["Auto Dough V2"] or _G.Settings.Main["Auto Holy Torch"] or
				_G.Settings.Main["Auto Buddy Swords"] or _G.Settings.Main["Auto Farm Boss Hallow"] or _G.Settings.Main["Mob Aura"] or _G.Settings.Main["Auto Material Soul Guitar"] or _G.Settings.Main["Auto Quest Soul Guitar"] or YamaQuest2 or YamaQuest1 or Auto_Cursed_Dual_Katana or
				Tushita_Quest2 or Tushita_Quest1 or AutoFarmMaterial or teleporttop or AutoFarmChest or 
				--[For God Human]
				--_G.Settings.Main["Auto Fish Tail Sea 1"] or _G.Settings.Main["Auto Fish Tail Sea 3"] or _G.Settings.Main["Auto Magma Ore Sea 2"] or 
				--_G.Settings.Main["Auto Magma Ore Sea 1"] or _G.Settings.Main["Auto Mystic Droplet"] or _G.Settings.Main["Auto Dragon Scales"] or 
				--[Boss]
				_G.Settings.Boss["Auto All Boss"] or _G.Settings.Boss["Auto Boss Select"] or
				--[Mastery]
				_G.Settings.Mastery["Auto Farm Fruit Mastery"] or _G.Settings.Mastery["Auto Farm Gun Mastery"] or _G.Settings.Mastery["Farm Mastery SwordList"] or
				--[Teleport]
				_G.Settings.Teleport["Teleport to Sea Beast"] or
				--[Raids]
				_G.Settings.Raids["Auto Raids"] or _G.Settings.Raids["Auto Next Place"]
			then
				if syn then
					setfflag("HumanoidParallelRemoveNoPhysics", "False")
					setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
					game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
					if game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Sit == true then
						game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Sit = false
					end
				else
					if game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart") then
						if not game:GetService("Players").LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyVelocity1") then
							if game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Sit == true then
								game.Players.LocalPlayer.Character:WaitForChild("Humanoid").Sit = false
							end
							local BodyVelocity = Instance.new("BodyVelocity")
							BodyVelocity.Name = "BodyVelocity1"
							BodyVelocity.Parent =  game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
							BodyVelocity.MaxForce = Vector3.new(10000, 10000, 10000)
							BodyVelocity.Velocity = Vector3.new(0, 0, 0)
						end
					end
					for _, v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
						if v:IsA("BasePart") then
							v.CanCollide = false    
						end
					end
				end
			else
				if game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyVelocity1") then
					game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyVelocity1"):Destroy();
				end
			end
		end)
	end)
end)

-- [Infinites Energy]

function InfinitiesEnergy()
	game:GetService('Players').LocalPlayer.Character.Energy.Changed:connect(function()
		if _G.Settings.Misc["Infinities Energy"] then
			game:GetService('Players').LocalPlayer.Character.Energy.Value = game:GetService('Players').LocalPlayer.Character.Energy.MaxValue
		end 
	end)
end

-- [No Cooldown , Infinities Geppo]

function NoCooldown()
	for i,v in next, getgc() do
		if typeof(v) == "function" then
			if getfenv(v).script == game.Players.LocalPlayer.Character:WaitForChild("Dodge") and _G.Settings.Misc["No Dash Cooldown"] then
				for i2,v2 in next, getupvalues(v) do
					if tostring(v2) == "0.4" then
						repeat wait(.1)
							setupvalue(v,i2,0)
						until not _G.Settings.Misc["No Dash Cooldown"]
					end
				end
			end
			if getfenv(v).script == game.Players.LocalPlayer.Character:WaitForChild("Geppo") and _G.Settings.Misc["Infinities Geppo"] then
				for i2,v2 in next, getupvalues(v) do
					if tostring(v2) == "0" then
						repeat wait(.1)
							setupvalue(v,i2,0)
						until not _G.Settings.Misc["Infinities Geppo"]
					end
				end
			end
			if getfenv(v).script == game.Players.LocalPlayer.Character:WaitForChild("Soru") and _G.Settings.Misc["No Soru Cooldown"] then
				for i2,v2 in pairs(debug.getupvalues(v)) do
					if type(v2) == 'table' then
						if v2.LastUse then
							repeat wait()
								setupvalue(v, i2, {LastAfter = 0,LastUse = 0})
							until not _G.Settings.Misc["No Soru Cooldown"]
						end
					end
				end
			end
		end
	end
end

-- [CheckMasteryWeapon]

function CheckMasteryWeapon(NameWe,MasNum)
	if game.Players.LocalPlayer.Backpack:FindFirstChild(NameWe) then
		if tonumber(game.Players.LocalPlayer.Backpack:FindFirstChild(NameWe).Level.Value) < tonumber(MasNum) then
			return "true DownTo"
		elseif tonumber(game.Players.LocalPlayer.Backpack:FindFirstChild(NameWe).Level.Value) >= tonumber(MasNum) then
			return "true UpTo"
		end
	end
	if game.Players.LocalPlayer.Character:FindFirstChild(NameWe) then
		if tonumber(game.Players.LocalPlayer.Character:FindFirstChild(NameWe).Level.Value) < tonumber(MasNum) then
			return "true DownTo"
		elseif tonumber(game.Players.LocalPlayer.Character:FindFirstChild(NameWe).Level.Value) >= tonumber(MasNum) then
			return "true UpTo"
		end
	end
	return "else"
end

--[GetWeaponInventory]

function GetWeaponInventory(Weaponname)
	for i,v in pairs(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventory")) do
		if type(v) == "table" then
			if v.Type == "Sword" then
				if v.Name == Weaponname then
					return true
				end
			end
		end
	end
	return false
end

-- [GetMaterial]

function GetMaterial(matname)
	for i,v in pairs(game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventory")) do
		if type(v) == "table" then
			if v.Type == "Material" then
				if v.Name == matname then
					return v.Count
				end
			end
		end
	end
	return 0
end

local AllMaterial
if Old_World then
	AllMaterial = {
		"Magma Ore",
		"Leather",
		"Scrap Metal",
		"Angel Wings",
		"Fish Tail"
	}
elseif New_World then
	AllMaterial = {
		"Magma Ore",
		"Scrap Metal",
		"Radioactive Material",
		"Vampire Fang",
		"Mystic Droplet",
	}
elseif Three_World then
	AllMaterial = {
		"Mini Tusk",
		"Fish Tail",
		"Scrap Metal",
		"Dragon Scale",
		"Conjured Cocoa",
		"Demonic Wisp",
		"Gunpowder",
	}
end

table.sort(AllMaterial)

-- [CustomFindFirstChild]

local function CustomFindFirstChild(tablename)
	for i,v in pairs(tablename) do
		if game:GetService("Workspace").Enemies:FindFirstChild(v) then
			return true
		end
	end
	return false
end



function TP(P)
    CheckQuest()
local Distance = (P.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude -- จุดที่จะไป Position Only
local Speed = 370 -- ความเร็วของมึง
tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = P})
tween:Play()
end

-----------Bypass
function ByPass(Position)
    game.Players.LocalPlayer.Character.Head:Destroy()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Position
    wait(.5)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Position
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
end




--------------------------------------------
-- UI System
local repo = 'https://raw.githubusercontent.com/Pakkasheed/wally-rblx/main/'

local Library = loadstring(game:HttpGet(repo .. 'LinoriaLib(Pak).lua'))()


Library:SetWatermarkVisibility(true)

function setwatermarktime()
    local dgt = math.floor(workspace.DistributedGameTime+0.27322)
    local hr = math.floor(dgt/(60^2))%24
    local min = math.floor(dgt/(60^1))%60
    local sec = math.floor(dgt/(60^0))%60
    Library:SetWatermark("Tara Hub Pc Editon 2.0 | "..hr.." Hour(s) "..min.." Minute(s) "..sec.." Second(s)")
 end
 
 spawn(function()
     while task.wait(0) do 
         pcall(function() setwatermarktime() 
         end) 
     end 
end)

local Window = Library:CreateWindow({
    Title = 'Tara Hub | Pc Editon 2.0',
    Center = true, 
    AutoShow = true,
})
local Tabs = {
    -- Creates a new tab titled Main
    ['General'] = Window:AddTab('General'), 
    ['info'] = Window:AddTab('Info'), 
	['Automatics'] = Window:AddTab('Automatics'),
    ['Teleport'] = Window:AddTab('Teleport'),
	['misc'] = Window:AddTab('misc'),
   
}
local GeneralBox = Tabs['General']:AddLeftTabbox()
local GeneralBox2 = Tabs['General']:AddLeftTabbox()
local GeneralBox3 = Tabs['Teleport']:AddLeftTabbox()
local GeneralBox4 = Tabs['Automatics']:AddLeftTabbox()
local GeneralBox5 = Tabs['misc']:AddLeftTabbox()
local SettingBox = Tabs['General']:AddRightTabbox()
local SettingBox2 = Tabs['General']:AddRightTabbox()
local InfoBox = Tabs['info']:AddLeftTabbox()
local InfoBox1 = Tabs['info']:AddLeftTabbox()
local InfoBox2 = Tabs['info']:AddRightTabbox()
local AutoFarm = GeneralBox:AddTab('Main')
local AutoFarm1 = GeneralBox:AddTab('Fighting')
local AutoFarm2 = GeneralBox:AddTab('Boss')
local AutoFarm3 = GeneralBox2:AddTab('Item')
local Automatics = GeneralBox4:AddTab('Automatics')
local misc = GeneralBox5:AddTab('misc')
local SettingGeneral = SettingBox:AddTab('Setting')
local SettingGeneral2 = SettingBox:AddTab('Stats')
local InfoPlayer1 = InfoBox:AddTab('Player Information')
local KaiTun6 = InfoBox1:AddTab('Sword Information')
local KaiTun5 = InfoBox2:AddTab('Melee Information')
local Teleport = GeneralBox3:AddTab('Teleport')

----------------------------------------
PlayerName = InfoPlayer1:AddLabel("")
LevelStast = InfoPlayer1:AddLabel("")
RaceInfo = InfoPlayer1:AddLabel("")
BeliInfo = InfoPlayer1:AddLabel("")
Fragments = InfoPlayer1:AddLabel("")
DevilFruitInfo = InfoPlayer1:AddLabel("")

---------------------------------
Superhuman = KaiTun5:AddLabel ("❌ : Superhuman")
DeathStep = KaiTun5:AddLabel("❌ : Death Step")
SharkmanKarate = KaiTun5:AddLabel( "❌ : Sharkman Karate")
ElectricClaw = KaiTun5:AddLabel( "❌ : Electric Claw")
DragonTalon = KaiTun5:AddLabel("❌ : Dragon Talon")
GodHuman = KaiTun5:AddLabel("❌ : God Human")
--------------------------------

Shisui = KaiTun6:AddLabel( "❌ : Shisui")
Saddi = KaiTun6:AddLabel( "❌ : Saddi")
Wando = KaiTun6:AddLabel("❌ : Wando")
TrueTripleKatana = KaiTun6:AddLabel("❌ : True Triple Katana")
Saber = KaiTun6:AddLabel("❌ : Saber")
Rengoku = KaiTun6:AddLabel("❌ : Rengoku")
MidnightBlade = KaiTun6:AddLabel("❌ : Midnight Blade")
DragonTrident = KaiTun6:AddLabel("❌ : DragonTrident")
Yama = KaiTun6:AddLabel( "❌ : Yama")
BuddySword = KaiTun6:AddLabel( "❌ : Buddy Sword")
Canvander = KaiTun6:AddLabel("❌ : Canvander")
TwinHooks = KaiTun6:AddLabel("❌ : Twin Hooks")
SpikeyTrident = KaiTun6:AddLabel("❌ : Spikey Trident")
HallowScythe = KaiTun6:AddLabel( "❌ : Hallow Scythe")
DarkDagger = KaiTun6:AddLabel( "❌ : Dark Dagger")
Tushita = KaiTun6:AddLabel( "❌ : Tushita")
CursedDualKatana = KaiTun6:AddLabel( "❌ : Cursed Dual Katana")

-------------------

task.spawn(
    function()
        pcall(
            function()
                while wait() do
                    Fragments:SetText("Fragments : " .. game:GetService("Players").localPlayer.Data.Fragments.value)
                end
            end
        )
    end
)

task.spawn(
    function()
        pcall(
            function()
                while wait() do
                    LevelStast:SetText("Level : " .. game:GetService("Players").localPlayer.Data.Level.value)
                end
            end
        )
    end
)

task.spawn(
    function()
        pcall(
            function()
                while wait() do
                    PlayerName:SetText("PlayerName : " .. game.Players.localPlayer.Name)
                end
            end
        )
    end
)

task.spawn(
    function()
        while task.wait() do
            if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman", true) == 1 then
                Superhuman:SetText("✅ : Superhuman")
            end
            if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep", true) == 1 then
                DeathStep:SetText("✅ : Death Step")
            end
            if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate", true) == 1 then
                SharkmanKarate:SetText("✅ : Sharkman Karate")
            end
            if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw", true) == 1 then
                ElectricClaw:SetText("✅ : Electric Claw")
            end
            if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon", true) == 1 then
                DragonTalon:SetText("✅ : Dragon Talon")
            end
            if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyGodHuman", true) == 1 then
                GodHuman:SetText("✅ : God Human")
            end
        end
    end
)
-- Sword Check
task.spawn(
    function()
        while task.wait() do
            pcall(
                function()
                    for i, v in pairs(
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventoryWeapons")
                    ) do
                        if v.Name == "Saber" then
                            Saber:SetText("✅ : Saber")
                        end
                        if v.Name == "Rengoku" then
                            Rengoku:SetText("✅ : Rengoku")
                        end
                        if v.Name == "Midnight Blade" then
                            MidnightBlade:SetText("✅ : Midnight Blade")
                        end
                        if v.Name == "Dragon Trident" then
                            DragonTrident:SetText("✅ : Dragon Trident")
                        end
                        if v.Name == "Yama" then
                            Yama:SetText("✅ : Yama")
                        end
                        if v.Name == "Buddy Sword" then
                            BuddySword:SetText("✅ : Buddy Sword")
                        end
                        if v.Name == "Canvander" then
                            Canvander:SetText("✅ : Canvander")
                        end
                        if v.Name == "Twin Hooks" then
                            TwinHooks:SetText("✅ : Twin Hooks")
                        end
                        if v.Name == "Spikey Trident" then
                            SpikeyTrident:SetText("✅ : Spikey Trident")
                        end
                        if v.Name == "Hallow Scythe" then
                            HallowScythe:SetText("✅ : Hallow Scythe")
                        end
                        if v.Name == "Dark Dagger" then
                            DarkDagger:SetText("✅ : Dark Dagger")
                        end
                        if v.Name == "Tushita" then
                            Tushita:SetText("✅ : Tushita")
                        end
                        if v.Name == "Cursed Dual Katana" then
                            CursedDualKatana:SetText("✅ : Cursed Dual Katana")
                        end
                    end
                end
            )
        end
    end
)

---------------- Gun Check ----------------
task.spawn(
    function()
        while task.wait() do
            pcall(
                function()
                    for i, v in pairs(
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventoryWeapons")
                    ) do
                        if v.Name == "Kabucha" then
                            Kabucha:SetText("✅ : Kabucha")
                        end
                        if v.Name == "Acidum Rifle" then
                            AcidumRifle:SetText("✅ : Acidum Rifle")
                        end
                        if v.Name == "Bizarre Rifle" then
                            BizarreRifle:SetText("✅ : Bizarre Rifle")
                        end
                    end
                end
            )
        end
    end
)



---------------- Legendary Sword Check ----------------
task.spawn(
    function()
        while task.wait() do
            pcall(
                function()
                    for i, v in pairs(
                        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventoryWeapons")
                    ) do
                        if v.Name == "Shisui" then
                            Shisui:SetText("✅ : Shisui")
                        end
                        if v.Name == "Saddi" then
                            Saddi:SetText("✅ : Saddi")
                        end
                        if v.Name == "Wando" then
                            Wando:SetText("✅ : Wando")
                        end
                        if v.Name == "True Triple Katana" then
                            TrueTripleKatana:SetText("✅ : True Triple Katana")
                        end
                    end
                end
            )
        end
    end
)
task.spawn(
    function()
        pcall(
            function()
                while wait() do
                    BeliInfo:SetText("Beli : " .. game:GetService("Players").localPlayer.Data.Beli.value)
                end
            end
        )
    end
)
task.spawn(
    function()
        pcall(
            function()
                while wait() do
                    DevilFruitInfo:SetText("DevilFruit : " .. game:GetService("Players").localPlayer.Data.DevilFruit.value)
                end
            end
        )
    end
)

task.spawn(
    function()
        pcall(
            function()
                while wait() do
                    LevelFarm:SetText("Level : " .. game:GetService("Players").localPlayer.Data.Level.value)
                end
            end
        )
    end
)

task.spawn(
    function()
        pcall(
            function()
                while wait() do
                    RaceInfo:SetText("Race : " .. game:GetService("Players").localPlayer.Data.Race.value)
                end
            end
        )
    end
)
QuestStatus = AutoFarm:AddLabel("Quest:")

spawn(function()
    while task.wait() do
        CheckQuest()
        if not string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,NameMon) then
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonQuest")
                end
        QuestStatus:SetText("Quest : "..QuestName.." | Level "..LevelQuest)
end
end)
LevelFarm = AutoFarm:AddLabel("Hello")

task.spawn(
    function()
        pcall(
            function()
                while wait() do
                    LevelFarm:SetText("Level : "..game.Players.LocalPlayer.Data.Level.Value)
                end
            end
        )
    end
)

StatusAutoFarm = AutoFarm:AddLabel('AutoFarm : ❌')

task.spawn(
    function()
        pcall(
            function()
                while wait() do
                    if AutoFarm == false then
                        StatusAutoFarm:SetText("AutoFarm : ❌")
                    elseif AutoFarm == true then
                        StatusAutoFarm:SetText("AutoFarm : ✅")
                    end
                end
            end
        )
    end
)
-- AutoFarmToggle
AutoFarm:AddToggle('AutoFarmLevel', {
    Text = 'Auto Farm [Level]',
    Default = _G.SaveSetting.AutoFarm,
})
AutoFarm:AddToggle('AutoFarmSky', {
    Text = 'Auto Farm [Skypiea]',
    Default = _G.SaveSetting.AutoFarmSky,
    Tooltip = 'Turn On When Level 40 to Level 100',
})
AutoFarm:AddToggle('NewWorld', {
    Text = 'Auto New World',
    Default = _G.SaveSetting.AutoNewWorld,
})

AutoFarm:AddToggle('AutoCandy', {
    Text = 'Auto Candy',
    Default = _G.Auto_Candy,
})

Toggles.AutoCandy:OnChanged(function(t)
    _G.Auto_Candy = t
end)

AutoFarm:AddToggle('AutoEventChest', {
    Text = 'Auto Event Chest',
    Default = _G.Auto_Event_Chest,
})

Toggles.AutoEventChest:OnChanged(function(t)
    _G.Auto_Event_Chest = t
end)

                               spawn(function()
               while task.wait(.1) do
                pcall(function()
                    if _G.Auto_Event_Chest then
                        CHEST = CFrame.new(-1042.29211, 16.1700726, -14443.6025, 0.885915995, 1.18890057e-07, 0.4638457, -1.04902362e-07, 1, -5.59569173e-08, -0.4638457, 9.14619769e-10, 0.885915995)
                        task.wait(.1)
                        CHEST = CFrame.new(-1058.97156, 16.1700554, -14430.0264, 0.987882674, -7.36659658e-08, 0.155202463, 8.54428421e-08, 1, -6.92098467e-08, -0.155202463, 8.16321517e-08, 0.987882674)
                        task.wait(.1)
                        CHEST = CFrame.new(-1072.98767, 16.1700497, -14426.6533, 0.992732286, -3.45507445e-08, 0.120343804, 3.841145e-08, 1, -2.97609208e-08, -0.120343804, 3.41672042e-08, 0.992732286)
                        task.wait(.1)
                        CHEST = CFrame.new(-1094.90173, 16.1698418, -14427.958, 0.925672352, 3.50478158e-09, -0.378326178, -3.08392578e-09, 1, 1.71829706e-09, 0.378326178, -4.23850177e-10, 0.925672352)
                        task.wait(.1)
                        CHEST = CFrame.new(-1110.17041, 16.1698627, -14437.1602, 0.797869265, -9.89724782e-08, -0.602830529, 7.11797554e-08, 1, -6.99704827e-08, 0.602830529, 1.29179707e-08, 0.797869265)
                        task.wait(.1)
                        CHEST = CFrame.new(-1119.87915, 16.1698742, -14451.0273, 0.493415713, 9.11099551e-09, -0.869793594, -3.68680353e-09, 1, 8.38344771e-09, 0.869793594, -9.29766708e-10, 0.493415713)
                        task.wait(.1)
                        CHEST = CFrame.new(-1128.72388, 16.1698875, -14471.0352, 0.121122606, 4.55449936e-08, -0.992637575, -1.01489466e-08, 1, 4.46444197e-08, 0.992637575, 4.66677719e-09, 0.121122606)
                        task.wait(.1)
                        CHEST = CFrame.new(-1127.0813, 16.1698875, -14489.8535, -0.322223634, 3.48246694e-08, -0.946663558, 3.5995158e-09, 1, 3.55615448e-08, 0.946663558, 8.05124056e-09, -0.322223634)
                        task.wait(.1)
                        CHEST = CFrame.new(-1119.15906, 16.1699162, -14508.2158, -0.615767896, -9.78910393e-08, -0.787927568, -3.70835593e-08, 1, -9.52577039e-08, 0.787927568, -2.94374782e-08, -0.615767896)
                        task.wait(.1)
                        CHEST = CFrame.new(-1103.34326, 16.1698933, -14521.54, -0.855599821, -6.24879988e-08, -0.517637908, -5.50311867e-08, 1, -2.97569596e-08, 0.517637908, 3.02617975e-09, -0.855599821)
                        task.wait(.1)
                        CHEST = CFrame.new(-1083.96106, 16.1698723, -14528.1611, -0.990850925, -6.64650068e-09, -0.134960696, -4.34567493e-09, 1, -1.73427104e-08, 0.134960696, -1.65975464e-08, -0.990850925)
                        task.wait(.1)
                        CHEST = CFrame.new(-1066.05115, 16.169899, -14523.3203, -0.975328386, -6.58504629e-09, 0.220759079, -1.01085744e-08, 1, -1.48312509e-08, -0.220759079, -1.66968999e-08, -0.975328386)
                        task.wait(.1)
                        CHEST = CFrame.new(-1047.42346, 16.1699295, -14514.8057, -0.773561895, 2.21849508e-08, 0.633720815, 6.07934609e-08, 1, 3.92011046e-08, -0.633720815, 6.88505608e-08, -0.773561895)
                        task.wait(.1)
                        CHEST = CFrame.new(-1036.13977, 16.1699085, -14499.3125, -0.441327631, 6.57927224e-09, 0.89734602, 3.14423119e-08, 1, 8.13185519e-09, -0.89734602, 3.18034452e-08, -0.441327631)
                        task.wait(.1)
                        CHEST = CFrame.new(-1027.93433, 16.1698818, -14481.1553, -0.123675741, 3.17823812e-09, 0.992322683, 5.10409279e-08, 1, 3.15853543e-09, -0.992322683, 5.10397058e-08, -0.123675741)
                        task.wait(.1)
                        CHEST = CFrame.new(-1029.8927, 16.1701088, -14462.1279, 0.234415829, -2.59936517e-09, 0.972136438, 3.00987182e-08, 1, -4.58397675e-09, -0.972136438, 3.03346184e-08, 0.234415829)
                        task.wait(.1)
                        CHEST = CFrame.new(-1039.79004, 16.1700783, -14444.3467, 0.620080054, 3.42330893e-08, 0.784538567, -1.0041218e-07, 1, 3.57286467e-08, -0.784538567, -1.0093185e-07, 0.620080054)
                        task.wait(.1)
                        CHEST = CFrame.new(-1055.302, 16.1700573, -14431.6045, 0.887699246, -2.32200499e-08, 0.460423768, 4.36673595e-08, 1, -3.3758969e-08, -0.460423768, 5.00733002e-08, 0.887699246)
                        task.wait(.1)
                        CHEST = CFrame.new(-1073.89136, 16.1700459, -14426.3711, 0.991108298, 3.29777379e-08, 0.133057579, -4.26259064e-08, 1, 6.96627254e-08, -0.133057579, -7.4715004e-08, 0.991108298)
                        task.wait(.1)
                        CHEST = CFrame.new(-1092.79199, 16.169836, -14428.165, 0.976551235, -4.82434501e-08, -0.215285167, 2.47044927e-08, 1, -1.12029298e-07, 0.215285167, 1.04083838e-07, 0.976551235)
                        task.wait(.1)   
                        CHEST = CFrame.new(-1109.89636, 16.1698608, -14437.0254, 0.801058233, -7.48542472e-09, -0.59858638, -3.04755616e-08, 1, -5.32890922e-08, 0.59858638, 6.09299207e-08, 0.801058233)
                        task.wait(.1)
                        CHEST = CFrame.new(-1122.53943, 16.1698799, -14451.9072, 0.50399375, 1.22311605e-09, -0.863707304, -2.27240946e-08, 1, -1.18439267e-08, 0.863707304, 2.55962327e-08, 0.50399375)
                    end
                end)
               end
                               end)
       
    spawn(function()
               game:GetService("RunService").Heartbeat:Connect(function()
                pcall(function()
                    if _G.Auto_Event_Chest then
                        game:GetService("VirtualInputManager"):SendKeyEvent(true,"E",false,game)
game:GetService("VirtualInputManager"):SendKeyEvent(false,"E",false,game)
                        end
                end)
               end)
end)
        
spawn(function()
               game:GetService("RunService").Heartbeat:Connect(function()
                pcall(function()
                    if _G.Auto_Event_Chest then
 local Distance2 = (game:GetService("Workspace").LOL.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
if Distance2 >= 101 then
    local tween_s = game:service"TweenService"
    local info = TweenInfo.new(Distance2/350, Enum.EasingStyle.Linear)
    local tween = tween_s:Create(game:GetService("Players").LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = game:GetService("Workspace").LOL.CFrame})
    tween:Play()  
    elseif Distance2 <= 100 then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").LOL.CFrame
            end
                end
                end)
               end)
end)
                           
            spawn(function()
                game:GetService("RunService").Heartbeat:Connect(function()
                    if _G.Auto_Event_Chest then
                        if not game:GetService("Workspace"):FindFirstChild("LOL") then
                            local LOL = Instance.new("Part")
                            LOL.Name = "LOL"
                            LOL.Parent = game.Workspace
                            LOL.Anchored = true
                            LOL.Transparency = 1
                            LOL.Size = Vector3.new(7,-0.2,7)
                            LOL.Material = "Neon"
                        elseif game:GetService("Workspace"):FindFirstChild("LOL") then
                            game.Workspace["LOL"].CFrame = CHEST
                        end
                    end
                end)
            end)

------Automatics-------
Automatics:AddToggle('EliteHunter', {
    Text = 'Auto Elite Hunter',
    Default = false,
})	

------misc-------
misc:AddButton('CapCut Picture Kaitan', function()
    local cac = require(game:GetService("Players").LocalPlayer.PlayerGui.Main.UIController.Inventory)
		local Inventory = game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventory")
		local Items = {}
		local RaityLevel = {"Mythical","Legendary","Rare","Uncommon","Common"}
		local RaityColor =  {
			["Common"] = Color3.fromRGB(179, 179, 179),
			["Uncommon"] = Color3.fromRGB(92, 140, 211),
			["Rare"] =  Color3.fromRGB(140, 82, 255),
			["Legendary"] = Color3.fromRGB(213, 43, 228) ,
			["Mythical"] =  Color3.fromRGB(238, 47, 50)
		}
		function GetRaity(color)
			for k,v in pairs(RaityColor) do 
				if v==color then return k end
			end
		end

		for k,v in pairs(Inventory) do 
			Items[v.Name] = v
		end

		local total = #getupvalue(cac.UpdateRender,4)
		local rac = {}
		local allitem = {}
		local total2 = 0
		while total2<total do 
			local i = 0
			while i < 25000 and total2<total do 
				game:GetService("Players").LocalPlayer.PlayerGui.Main.InventoryContainer.Right.Content.ScrollingFrame.CanvasPosition = Vector2.new(0,i)
				for k,v in pairs(game:GetService("Players").LocalPlayer.PlayerGui.Main.InventoryContainer.Right.Content.ScrollingFrame.Frame:GetChildren()) do 
					if v:IsA("Frame") and not rac[v.ItemName.Text] and v.ItemName.Visible==true then 
						local vaihuhu = GetRaity(v.Background.BackgroundColor3)
						if vaihuhu then
							print("Rac")
							if not allitem[vaihuhu] then 
								allitem[vaihuhu] = {}
							end
							table.insert(allitem[vaihuhu],v:Clone())
						end
						total2=total2+1
						rac[v.ItemName.Text] = true
					end
				end
				i=i+20
			end
			wait()
		end
		function GetXY(vec) 
			return vec*100
		end

		local tvk = Instance.new("UIListLayout")
		tvk.FillDirection = Enum.FillDirection.Vertical
		tvk.SortOrder = 2
		tvk.Padding = UDim.new(0,10)

		local Left = Instance.new("Frame",game.Players.LocalPlayer.PlayerGui.BubbleChat)
		Left.BackgroundTransparency = 1
		Left.Size = UDim2.new(.5,0,1,0) 
		tvk.Parent = Left

		local Right = Instance.new("Frame",game.Players.LocalPlayer.PlayerGui.BubbleChat)
		Right.BackgroundTransparency = 1
		Right.Size = UDim2.new(.5,0,1,0) 
		Right.Position = UDim2.new(.6,0,0,0)
		tvk:Clone().Parent = Right
		for k,v in pairs(allitem) do 
			local cac = Instance.new("Frame",Left)
			cac.BackgroundTransparency = 1
			cac.Size = UDim2.new(1,0,0,0) 
			cac.LayoutOrder = table.find(RaityLevel,k)

			local cac2 = Instance.new("Frame",Right)
			cac2.BackgroundTransparency = 1
			cac2.Size = UDim2.new(1,0,0,0) 
			cac2.LayoutOrder = table.find(RaityLevel,k)

			local tvk = Instance.new("UIGridLayout",cac)
			tvk.CellPadding = UDim2.new(.005,0,.005,0)
			tvk.CellSize =  UDim2.new(0,70,0,70)
			tvk.FillDirectionMaxCells = 100
			tvk.FillDirection = Enum.FillDirection.Horizontal

			local ccc = tvk:Clone()
			ccc.Parent = cac2
			for k,v in pairs(v) do 
				if Items[v.ItemName.Text] and Items[v.ItemName.Text].Mastery then 
					if v.ItemLine2.Text~="Accessory" then 
						local bucac = v.ItemName:Clone()
						bucac.BackgroundTransparency = 1
						bucac.TextSize = 10
						bucac.TextXAlignment  = 2
						bucac.TextYAlignment  = 2
						bucac.ZIndex  = 5
						bucac.Text = Items[v.ItemName.Text].Mastery
						bucac.Size = UDim2.new(.5,0,.5,0)
						bucac.Position = UDim2.new(.5,0,.5,0)
						bucac.Parent = v
					end
					v.Parent = cac
				elseif v.ItemLine2.Text == "Blox Fruit" then 
					v.Parent = cac2
				end
			end
			cac.AutomaticSize = 2
			cac2.AutomaticSize = 2
		end
		local ListHuhu = {
			["Superhuman"] = Vector2.new(3,2),
			["DeathStep"] = Vector2.new(4,3),
			["ElectricClaw"] = Vector2.new(2,0),
			["SharkmanKarate"] = Vector2.new(0,0),
			["DragonTalon"] = Vector2.new(1,5)
		}
		local MeleeG = Instance.new("Frame",Left)
		MeleeG.BackgroundTransparency = 1
		MeleeG.Size = UDim2.new(1,0,0,0) 
		MeleeG.LayoutOrder = table.find(RaityLevel,k)
		MeleeG.AutomaticSize=2
		MeleeG.LayoutOrder = 100
		local tvk = Instance.new("UIGridLayout",MeleeG)
		tvk.CellPadding = UDim2.new(.005,0,.005,0)
		tvk.CellSize =  UDim2.new(0,70,0,70)
		tvk.FillDirectionMaxCells = 100
		tvk.FillDirection = Enum.FillDirection.Horizontal

		local cac = {"Superhuman","ElectricClaw","DragonTalon","SharkmanKarate","DeathStep","GodHuman"}
		for k,v in pairs(cac) do
			if ListHuhu[v] and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buy"..v,true) == 1 then 
				local huhu = Instance.new("ImageLabel",MeleeG)
				huhu.Image = "rbxassetid://9945562382"
				huhu.ImageRectSize = Vector2.new(100,100)
				huhu.ImageRectOffset = ListHuhu[v]*100
			end
		end
		function formatNumber(v)
			return tostring(v):reverse():gsub("%d%d%d", "%1,"):reverse():gsub("^,", "")
		end
		game:GetService("Players").LocalPlayer.PlayerGui.Main.Beli.Position = UDim2.new(0,800,0,500)
		game:GetService("Players").LocalPlayer.PlayerGui.Main.Level.Position = UDim2.new(0,800,0,550)

		local thieunang = game:GetService("Players").LocalPlayer.PlayerGui.Main.Fragments:Clone()
		thieunang.Parent = game:GetService("Players").LocalPlayer.PlayerGui.BubbleChat
		thieunang.Position = UDim2.new(0,800,0.63,0)
		local n = formatNumber(game.Players.LocalPlayer.Data.Fragments.Value)
		thieunang.Text = "ƒ"..n
		print("Done")
		pcall(function() 
			game:GetService("Players").LocalPlayer.PlayerGui.Main.MenuButton:Destroy()
		end)
		pcall(function() 
			game:GetService("Players").LocalPlayer.PlayerGui.Main.HP:Destroy()
		end)
		pcall(function() 
			game:GetService("Players").LocalPlayer.PlayerGui.Main.Energy:Destroy()
		end)
		for k,v in pairs(game:GetService("Players").LocalPlayer.PlayerGui.Main:GetChildren()) do 
			if v:IsA("ImageButton") then 
				v:Destroy()
			end
		end
		pcall(function() 
			game:GetService("Players").LocalPlayer.PlayerGui.Main.Compass:Destroy()
		end)
end)

misc:AddButton('Remove Picture Kaitan', function()
    game:GetService("TeleportService"):Teleport(game.PlaceId, game:GetService("Players").localPlayer)
end)

misc:AddButton('Devil Fruit Shop', function()
	local args = {
        [1] = "GetFruits"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    game.Players.localPlayer.PlayerGui.Main.FruitShop.Visible = true
end)
misc:AddButton('Devil Fruit Inventory', function()
	local args = {
		[1] = "getInventoryFruits"
	}
	
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventoryFruits")
	game:GetService("Players").LocalPlayer.PlayerGui.Main.FruitInventory.Visible = true
end)
misc:AddButton('Inventory', function()
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("getInventoryWeapons")
    game.Players.localPlayer.PlayerGui.Main.Inventory.Visible = true
end)
misc:AddButton('Title Name', function()
    local args = {
        [1] = "getTitles"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    game.Players.localPlayer.PlayerGui.Main.Titles.Visible = true
end)
misc:AddButton('Color Haki', function()
    game.Players.localPlayer.PlayerGui.Main.Colors.Visible = true
end)
misc = misc:AddLabel ("Buy")


------item-------

AutoFarm3:AddToggle('AutoSaber', {
    Text = 'Auto Saber',
	Default = _G.Settings.Main["Auto Saber"],
	callback = function(value)
		_G.Settings.Main["Auto Saber"] = value
		if value == false then
			wait()
			toTarget(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
			wait()
		end
		SaveSettings()
		task.spawn(function()
			while wait() do
				pcall(function()
					if _G.Settings.Main["Auto Saber"] and game.Players.LocalPlayer.Data.Level.Value >= 200 and not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Saber") and not game.Players.LocalPlayer.Character:FindFirstChild("Saber") then
						if Auto_Farm_Level then
							_G.Settings.Main["Auto Farm Level"] = false
						end
						if game:GetService("Workspace").Map.Jungle.Final.Part.Transparency == 0 then
							if game:GetService("Workspace").Map.Jungle.QuestPlates.Door.Transparency == 0 then
								if (CFrame.new(-1612.55884, 36.9774132, 148.719543, 0.37091279, 3.0717151e-09, -0.928667724, 3.97099491e-08, 1, 1.91679348e-08, 0.928667724, -4.39869794e-08, 0.37091279).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 100 then
									toTarget(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame)
									wait(1)
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Jungle.QuestPlates.Plate1.Button.CFrame
									wait(1)
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Jungle.QuestPlates.Plate2.Button.CFrame
									wait(1)
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Jungle.QuestPlates.Plate3.Button.CFrame
									wait(1)
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Jungle.QuestPlates.Plate4.Button.CFrame
									wait(1)
									game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Jungle.QuestPlates.Plate5.Button.CFrame
									wait(1) 
								else
									toTarget(CFrame.new(-1612.55884, 36.9774132, 148.719543, 0.37091279, 3.0717151e-09, -0.928667724, 3.97099491e-08, 1, 1.91679348e-08, 0.928667724, -4.39869794e-08, 0.37091279))
								end
							else
								if game:GetService("Workspace").Map.Desert.Burn.Part.Transparency == 0 then
									if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Torch") or game.Players.LocalPlayer.Character:FindFirstChild("Torch") then
										EquipWeapon("Torch")
										toTarget(CFrame.new(1114.61475, 5.04679728, 4350.22803, -0.648466587, -1.28799094e-09, 0.761243105, -5.70652914e-10, 1, 1.20584542e-09, -0.761243105, 3.47544882e-10, -0.648466587))
									else
										toTarget(CFrame.new(-1610.00757, 11.5049858, 164.001587, 0.984807551, -0.167722285, -0.0449818149, 0.17364943, 0.951244235, 0.254912198, 3.42372805e-05, -0.258850515, 0.965917408))                 
									end
								else
									if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","SickMan") ~= 0 then
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","GetCup")
										wait(0.5)
										EquipWeapon("Cup")
										wait(0.5)
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","FillCup",game:GetService("Players").LocalPlayer.Character.Cup)
										wait(0)
										game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","SickMan") 
									else
										if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","RichSon") == nil then
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","RichSon")
										elseif  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","RichSon") == 0 then
											if game:GetService("Workspace").Enemies:FindFirstChild("Mob Leader [Lv. 120] [Boss]") or game:GetService("ReplicatedStorage"):FindFirstChild("Mob Leader [Lv. 120] [Boss]") then
												toTarget(CFrame.new(-2967.59521, -4.91089821, 5328.70703, 0.342208564, -0.0227849055, 0.939347804, 0.0251603816, 0.999569714, 0.0150796166, -0.939287126, 0.0184739735, 0.342634559))
												for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
													if v.Name == "Mob Leader [Lv. 120] [Boss]" then
														repeat wait()
															StartMagnet = true
															FastAttack = true
															if _G.Settings.Configs["Auto Haki"] then
																if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
																	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
																end
															end
															if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
																wait()
																EquipWeapon(_G.Settings.Configs["Select Weapon"])
															end
															toTarget(v.HumanoidRootPart.CFrame * CFrame.new(0,_G.Settings.Configs["Distance Auto Farm"],0))
															PosMon = v.HumanoidRootPart.CFrame
															if not _G.Settings.Configs["Fast Attack"] then
																game:GetService'VirtualUser':CaptureController()
																game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
															end
															v.HumanoidRootPart.Size = Vector3.new(60,60,60)
															if _G.Settings.Configs["Show Hitbox"] then
																v.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
															else
																v.HumanoidRootPart.Transparency = 1
															end
															v.Humanoid.JumpPower = 0
															v.Humanoid.WalkSpeed = 0
															v.HumanoidRootPart.CanCollide = false
															v.Humanoid:ChangeState(11)
														until v.Humanoid.Health <= 0 or _G.Settings.Main["Auto Saber"] == false
													end
												end
											end
										elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","RichSon") == 1 then
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","RichSon")
											wait(0.5)
											EquipWeapon("Relic")
											wait(0.5)
											toTarget(CFrame.new(-1404.91504, 29.9773273, 3.80598116, 0.876514494, 5.66906877e-09, 0.481375456, 2.53851997e-08, 1, -5.79995607e-08, -0.481375456, 6.30572643e-08, 0.876514494))
										end
									end
								end
							end
						else
							if game:GetService("Workspace").Enemies:FindFirstChild("Saber Expert [Lv. 200] [Boss]") or game:GetService("ReplicatedStorage"):FindFirstChild("Saber Expert [Lv. 200] [Boss]") then
								toTarget(CFrame.new(-1401.85046, 29.9773273, 8.81916237, 0.85820812, 8.76083845e-08, 0.513301849, -8.55007443e-08, 1, -2.77243419e-08, -0.513301849, -2.00944328e-08, 0.85820812))
								for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
									if v.Name == "Saber Expert [Lv. 200] [Boss]" then
										repeat wait()
											StartMagnet = true
											FastAttack = true
											if _G.Settings.Configs["Auto Haki"] then
												if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
													game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Buso")
												end
											end
											if not game.Players.LocalPlayer.Character:FindFirstChild(_G.Settings.Configs["Select Weapon"]) then
												wait()
												EquipWeapon(_G.Settings.Configs["Select Weapon"])
											end
											toTarget(v.HumanoidRootPart.CFrame * CFrame.new(0,_G.Settings.Configs["Distance Auto Farm"],0))
											PosMon = v.HumanoidRootPart.CFrame
											if not _G.Settings.Configs["Fast Attack"] then
												game:GetService'VirtualUser':CaptureController()
												game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
											end
											v.HumanoidRootPart.Size = Vector3.new(60,60,60)
											if _G.Settings.Configs["Show Hitbox"] then
												v.HumanoidRootPart.Transparency = _G.Hitbox_LocalTransparency
											else
												v.HumanoidRootPart.Transparency = 1
											end
											v.Humanoid.JumpPower = 0
											v.Humanoid.WalkSpeed = 0
											v.HumanoidRootPart.CanCollide = false
											v.Humanoid:ChangeState(11)
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("SetSpawnPoint")
										until v.Humanoid.Health <= 0 or _G.Settings.Main["Auto Saber"] == false
										if v.Humanoid.Health <= 0 then
											game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ProQuestProgress","PlaceRelic")
										end
										_G.Settings.Main["Auto Farm Level"] = true
									end
								end
							end
						end
					end
				end)
			end
		end)
	end,
})

AutoFarm3:AddToggle('WhiteScreen', {
    Text = 'White Screen',
    Default = false,
})

Toggles.WhiteScreen:OnChanged(function(t)
    _G.White_Screen = t
    savesettings()
end)

spawn(function()
    while wait() do
        if _G.White_Screen then
            game:GetService("RunService"):Set3dRenderingEnabled(false)
            else
                game:GetService("RunService"):Set3dRenderingEnabled(true)
        end
        end
                end)

AutoFarm3:AddToggle('AUTOFARMKATAKURI', {
    Text = 'Auto Farm Katakuri',
	Default = false,
})

Toggles.AUTOFARMKATAKURI:OnChanged(function(t)
    _G.KATAKURI = t
    savesettings()
end)

    spawn(function()
    	while wait() do
    		if _G.KATAKURI then
    			repeat wait() until game.CoreGui:FindFirstChild('RobloxPromptGui')
    			local lp,po,ts = game:GetService('Players').LocalPlayer,game.CoreGui.RobloxPromptGui.promptOverlay,game:GetService('TeleportService')							
    			po.ChildAdded:connect(function(a)
    				if a.Name == 'ErrorPrompt' then
    					repeat
    						ts:Teleport(7449423635)
    						wait(2)
    					until false
    				end
    			end)
    		end
    	end
    end)

    spawn(function()
        game:GetService("RunService").RenderStepped:Connect(function()
            pcall(function()
                if _G.KATAKURI then
                    if game:GetService("Workspace").Enemies:FindFirstChild("Cake Prince [Lv. 2300] [Raid Boss]") then
                            Mon = "Cake Prince [Lv. 2300] [Raid Boss]"
                            CFMN = "NON"
                        elseif game:GetService("Workspace").Enemies:FindFirstChild("Cookie Crafter [Lv. 2200]") then
                            Mon = "Cookie Crafter [Lv. 2200]"
                            CFMN = CFrame.new(-2375.37109, 37.8240471, -12132.6592, 0.371290624, 0, 0.928516686, 0, 1, 0, -0.928516686, 0, 0.371290624)
                        elseif game:GetService("Workspace").Enemies:FindFirstChild("Cake Guard [Lv. 2225]") then
                            Mon = "Cake Guard [Lv. 2225]"
                            CFMN = CFrame.new(-1547.46704, 37.8239517, -12256.4502, -0.863587916, 1.35471945e-08, -0.504198313, -1.54829394e-08, 1, 5.33878683e-08, 0.504198313, 5.39115916e-08, -0.863587916)
                        elseif game:GetService("Workspace").Enemies:FindFirstChild("Baking Staff [Lv. 2250]") then
                            Mon = "Baking Staff [Lv. 2250]"
                            CFMN = CFrame.new(-1838.87097, 37.8239822, -12930.1797, 0.999966979, -4.56582017e-09, 0.0081237359, 4.51649829e-09, 1, 6.08966477e-09, -0.0081237359, -6.05277295e-09, 0.999966979)
                        elseif game:GetService("Workspace").Enemies:FindFirstChild("Head Baker [Lv. 2275]") then
                            Mon = "Head Baker [Lv. 2275]"
                            CFMN = CFrame.new(-2246.24707, 53.5282593, -12863.1514, 0.83096534, 6.33553432e-10, 0.556324184, 2.73355644e-11, 1, -1.17965093e-09, -0.556324184, 9.95456495e-10, 0.83096534)
                            end
                    end
                end)
               end)
            end)


    spawn(function()
               game:GetService("RunService").RenderStepped:Connect(function()
                pcall(function()
                    if _G.KATAKURI then
                local Distance2 = (game:GetService("Workspace").Enemies[Mon].HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                local tween_s = game:service"TweenService"
                local info = TweenInfo.new(Distance2/350, Enum.EasingStyle.Linear)
                local tween = tween_s:Create(game:GetService("Players").LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = game:GetService("Workspace").Enemies[Mon].HumanoidRootPart.CFrame * CFrame.new(0,45,0)})
                tween:Play()
        local CombatFramework = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
            local Camera = require(game.ReplicatedStorage.Util.CameraShaker)
            Camera:Stop()
            getupvalues(CombatFramework)[2].activeController.hitboxMagnitude = 80
getupvalues(CombatFramework)[2]['activeController']:attack()  
                end
                end)
               end)
    end)
        
                    spawn(function()
               game:GetService("RunService").RenderStepped:Connect(function()
                pcall(function()
                    if _G.KATAKURI then
                if not game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                local args = {
            	[1] = "Buso"
            	}
            	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
            end
            end
            end)
            end)
                    end)
        
                   spawn(function()
               game:GetService("RunService").RenderStepped:Connect(function()
                pcall(function()
                    if _G.KATAKURI then
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                for i2,v2 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                    if v.Name == Mon and v2.Name == Mon then
                                        v2.HumanoidRootPart.CFrame = CFMN
                                        v2.HumanoidRootPart.CanCollide = false
                                        v.Humanoid:ChangeState(11)
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    if v.Humanoid:FindFirstChild("Animator") then
                                        v.Humanoid.Animator:Destroy()
                                    end
                                        sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                                    end
                                end
            end
                        
                    end
                end)
                end)
                end)
                   
                               spawn(function()
               game:GetService("RunService").RenderStepped:Connect(function()
                pcall(function()
                    if _G.KATAKURI then
                    
                    if game:GetService("Workspace").Enemies[Mon].Humanoid.Health == 0 then
        game:GetService("Workspace").Enemies[Mon]:Destroy()
        end
        end
        end)
        end)
                               end)
    
                               spawn(function()
               game:GetService("RunService").RenderStepped:Connect(function()
                pcall(function()
                    if _G.KATAKURI then
local args = {
    [1] = "CakePrinceSpawner",
    [2] = true
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end
        end)
        end)
        end)
        
                spawn(function()
                game:GetService("RunService").Heartbeat:Connect(function()
                    if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") and _G.KATAKURI or _G.Auto_Candy then
                        setfflag("HumanoidParallelRemoveNoPhysics", "False")
                        setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
                        game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
                    end
                end)
                end)
        
              spawn(function()
            game:GetService('RunService').Stepped:Connect(function()
                if _G.KATAKURI then
                    for i, v in pairs(game.Workspace["_WorldOrigin"]:GetChildren()) do
                        if v.Name == "CurvedRing" or v.Name == "SwordSlash" or v.Name == "Sounds" or v.Name == "SlashHit" or v.Name == "DamageCounter" then--or v.Name == "SlashHit"
                            v:Destroy() 
                        end
                    end
                end
            end)
        end)
        local Client = game.Players.LocalPlayer
        local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
        local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
        spawn(function()
            while task.wait() do
                if _G.KATAKURI then
                    pcall(function()
                        if not shared.orl then shared.orl = STOPRL.wrapAttackAnimationAsync end
                        if not shared.cpc then shared.cpc = STOP.play end
                            STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
                            local Hits = STOPRL.getBladeHits(b,c,d)
                            if Hits then
                                STOP.play = function() end
                                a:Play(0.01,0.01,0.01)
                                func(Hits)
                                STOP.play = shared.cpc
                                wait(a.length * 0.5)
                                a:Stop()
                            end
                        end
                    end)
                end
            end
        end)
        


Toggles.NewWorld:OnChanged(function(t)
    _G.SaveSetting.AutoNewWorld = t
    savesettings()
end)
Toggles.AutoFarmSky:OnChanged(function(t)
    _G.SaveSetting.AutoFarmSky = t
    savesettings()
    AutoFarmSky = t
end)

local Lvl = game.Players.LocalPlayer.Data.Level.Value
spawn(function()
	while wait() do
		pcall(function()
			if AutoFarmSky then
			    if Lvl == 20 or Lvl <= 100 then
		        AutoFarm = false
			    MonPos = CFrame.new(-7685, 5567, -502)
			    if AutoFarmSky and (MonPos.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 3000 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))
					end
					if game.Workspace.Enemies:FindFirstChild("Shanda [Lv. 475]") then
					    Bringmob = true
						for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
							if v.Name == "Shanda [Lv. 475]" and v.Humanoid.Health > 0 then
								if v.Humanoid.Health > 0 then
								    
                repeat wait()
                    _G.PosMon = v.HumanoidRootPart.CFrame
                    Equip(WeaponName)
                    AutoHaki()
                    HealthMin = v.Humanoid.MaxHealth * 100 / 100
                    Piwwy = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,30,0)
                        if v.Humanoid.Health > HealthMin then
                    Distance = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude 
                    Speed = 300 
                    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
                    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,30,0)})
                    tween:Play() 
                    else
                    Distance = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude 
                    Speed = 300 
                    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
                    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,30,0)})
                    tween:Play()
                        end
                    v.HumanoidRootPart.Size = Vector3.new(60,60,60)
                        v.HumanoidRootPart.CanCaillde = false
                    until AutoFarmSky == false or v.Humanoid.Health <= 0
                if game.Players.LocalPlayer.Character.Humanoid.Health <= 0 then
                        AutoFarmSky = false
                        wait(0.25)
                        AutoFarmSky = true
                end
								end
                end
                end
						
					
			
				end
			end
end
		end)
			end
end)

spawn(function()
game:GetService("RunService").Heartbeat:Connect(function()
    if AutoFarmSky then
    if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
        setfflag("HumanoidParallelRemoveNoPhysics", "False")
        setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
        game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
        end
    end
end)
end)



Toggles.AutoFarmLevel:OnChanged(function(t)
    _G.SaveSetting.AutoFarm = t
    AutoFarm = t
    Bringmob = t
    savesettings()
end)

Weapon = {
	"Melee",
	"Sword",
	"Devil Fruit"
}


SettingGeneral:AddDropdown('SelectWeaponDropdown', {
    Values = Weapon,
    Default = "Melee",
    Multi = false,
    Text = 'Select Weapon / Weapons',
	Tooltip = 'Select your weapon',
})
FastAttack = {
    "Normal",
    "Extreme"
}
SettingGeneral:AddDropdown('FastAttackMode', {
    Values = FastAttack,
    Default = "Normal",
    Multi = false,
    Text = 'Attack Modes',
    Tooltip = 'Extreme might be kick',


})
Options.FastAttackMode:OnChanged(function(vu)
	FastAttackSpeed = vu
end)
task.spawn(function()
	while wait() do
		pcall(function()
		    if FastAttackSpeed == "Normal" then
		        _G.FastAttackNormalSpeed = true
		        else
		          _G.FastAttackNormalSpeed = false
		    end
		  
		        
	        if FastAttackSpeed == "Extreme" then
	            _G.FastAttackExtremeSpeed = true
	            else
	                _G.FastAttackExtremeSpeed = false
	            end
		end)
	end
end)

local PLACE3 = {
    "Mansion",
    "Port Town",
    "Hydra Island",
    "Great Tree",
    "Haunted Castle",
    "Peanut Island",
    "Ice Cream Island",
    "Cake Land",
    "Chocolate Island",
    "Sea Castle",
	"Test"
}

local PLACE2 = {
    "Cafe",
    "Kingdom Of Rose",
    "Green Zone",
    "Zombie Island (Graveyard)",
    "Snow Mountain",
    "Hot & Cold [Cold]",
    "Hot & Cold [Hot]",
    "Cursed Ship",
    "Ice Castle",
    "Forgotten Island"
}

local PLACE1 = {
    "Jungle",
    "Prison",
    "Middle Town",
    "Magma Town",
    "Desert",
    "Admiral",
    "Mob Leader",
    "Pirate Village",
    "Strater (Pirate)",
    "Strater (Marine)",
    "Fountain City",
    "FishMan",
    "Colosseum",
    "Sky Island",
    "Sky Island Upper",
    "Frozen Village"
}

if Three_World then
    _G.PLACEEEEE = PLACE3
end
if New_World then
    _G.PLACEEEEE = PLACE2
end
if Old_World then
    _G.PLACEEEEE = PLACE1
end

    spawn(function()
               game:GetService("RunService").RenderStepped:Connect(function()
                pcall(function()
                    if _G.PLACETP == "Mansion" then
                    Posiz = CFrame.new(-12544.832, 337.168274, -7550.896, 0.998756051, -4.78186486e-08, -0.0498636626, 4.40813395e-08, 1, -7.60502843e-08, 0.0498636626, 7.37576258e-08, 0.998756051)
                    end
                    if _G.PLACETP == "Port Town" then
                        Posiz = CFrame.new(-276.811646, 6.79260969, 5339.68213, 0.961105406, -8.75051995e-08, -0.276181787, 9.33668005e-08, 1, 8.07487943e-09, 0.276181787, -3.35470212e-08, 0.961105406)
                    end
                    if _G.PLACETP == "Hydra Island" then
                        Posiz = CFrame.new(5223.4668, 51.5449409, -1986.13965, 0.977938831, -1.56768785e-08, 0.208891451, 9.80692949e-09, 1, 2.91361886e-08, -0.208891451, -2.64448268e-08, 0.977938831)
                    end
                    if _G.PLACETP == "Great Tree" then
                        Posiz = CFrame.new(2306.75708, 25.915369, -6474.33936, -0.800354779, -3.81157825e-08, 0.599526703, -9.04919375e-08, 1, -5.7228263e-08, -0.599526703, -1.00055246e-07, -0.800354779)
                    end
                    if _G.PLACETP == "Haunted Castle" then
                        Posiz = CFrame.new(-9515.00098, 142.16748, 5534.05029, 0.999768972, 4.00890521e-09, 0.0214929413, -3.9828687e-09, 1, -1.25419286e-09, -0.0214929413, 1.16829957e-09, 0.999768972)
                    end
                    if _G.PLACETP == "Peanut Island" then
                        Posiz = CFrame.new(-2046.92676, 9.73851776, -9929.4707, -0.97925657, 4.19613357e-08, -0.202624306, 3.80296932e-08, 1, 2.32968596e-08, 0.202624306, 1.51078634e-08, -0.97925657)
                    end
                    if _G.PLACETP == "Ice Cream Island" then
                        Posiz = CFrame.new(-879.810303, 65.8821869, -10910.1455, 0.729498625, 3.34171246e-09, -0.683982253, 1.25574628e-09, 1, 6.22498231e-09, 0.683982253, -5.40002443e-09, 0.729498625)
                    end
                    if _G.PLACETP == "Cake Land" then
                        Posiz = CFrame.new(-1983.1416, 25.3655796, -11723.2227, -0.869008243, -3.38111725e-08, -0.494797647, -1.76638597e-08, 1, -3.73104676e-08, 0.494797647, -2.3683068e-08, -0.869008243)
                    end
                    if _G.PLACETP == "Chocolate Island" then
                        Posiz = CFrame.new(99.3026581, 24.7969818, -12092.8955, 0.499533683, -1.74111463e-08, -0.866294444, 8.9585761e-08, 1, 3.15596616e-08, 0.866294444, -9.3372762e-08, 0.499533683)
                    end
                    if _G.PLACETP == "Sea Castle" then
                        Posiz = CFrame.new(-5005.20166, 314.578186, -3009.58984, -0.377068639, -4.95820345e-08, 0.92618531, -2.32813875e-08, 1, 4.40552768e-08, -0.92618531, -4.95101604e-09, -0.377068639)
                    end
					if _G.PLACETP == "Test" then
                        Posiz = CFrame.new(-1039.45703, 16.8213272, -14123.207, -0.920414209, 3.9865764e-09, -0.3909446, 9.61290247e-09, 1, -1.24346924e-08, 0.3909446, -1.52031809e-08, -0.920414209)
                    end
                    if _G.PLACETP == "Cafe" then
                    Posiz = CFrame.new(-377.178741, 73.0827408, 288.89624, 0.993705988, -2.56767212e-08, 0.112019747, 3.59747823e-08, 1, -8.9909463e-08, -0.112019747, 9.33734583e-08, 0.993705988)
                    end
                    if _G.PLACETP == "Kingdom Of Rose" then
                    Posiz = CFrame.new(-11.8735867, 29.3393974, 2763.9939, 0.999184668, 1.38716993e-08, 0.0403731987, -1.14252368e-08, 1, -6.08269204e-08, -0.0403731987, 6.03160544e-08, 0.999184668)
                    end
                    if _G.PLACETP == "Green Zone" then
                    Posiz = CFrame.new(-2274.07642, 73.0287857, -2729.57007, 0.888743043, -2.79301844e-08, 0.458405763, 2.14207034e-08, 1, 1.93991525e-08, -0.458405763, -7.42148742e-09, 0.888743043)
                    end
                    if _G.PLACETP == "Zombie Island (Graveyard)" then
                    Posiz = CFrame.new(-5417.75049, 48.5428009, -723.571411, -0.34057793, 6.80824925e-08, -0.940216303, 2.83641786e-08, 1, 6.21370617e-08, 0.940216303, -5.50595125e-09, -0.34057793)
                    end
                    if _G.PLACETP == "Snow Mountain" then
                    Posiz = CFrame.new(565.735474, 401.484619, -5364.05615, -0.169436797, 5.01580786e-08, -0.985541046, -6.33883559e-08, 1, 6.17918445e-08, 0.985541046, 7.29416385e-08, -0.169436797)
                    end
                    if _G.PLACETP == "Hot & Cold [Cold]" then
                    Posiz = CFrame.new(-5968.06494, 16.0144272, -5090.50781, 0.318601072, -2.01137436e-08, -0.947888911, 2.77007768e-08, 1, -1.19088277e-08, 0.947888911, -2.24630945e-08, 0.318601072)
                    end
                    if _G.PLACETP == "Hot & Cold [Hot]" then
                    Posiz = CFrame.new(-5439.62061, 16.014431, -5233.58252, 0.325334907, 2.50246135e-08, -0.945598841, -1.03219399e-07, 1, -9.04851039e-09, 0.945598841, 1.00547943e-07, 0.325334907)
                    end
                    if _G.PLACETP == "Cursed Ship" then
                    Posiz = CFrame.new(923.058411, 125.119774, 32883.75, -0.995859385, -3.52043408e-08, 0.0909070522, -3.29793828e-08, 1, 2.59772115e-08, -0.0909070522, 2.28715908e-08, -0.995859385)
                    end
                    if _G.PLACETP == "Ice Castle" then
                    Posiz = CFrame.new(5701.23877, 28.4293079, -6395.31396, 0.814146578, 5.40739564e-10, -0.580659389, -1.60385691e-10, 1, 7.0637296e-10, 0.580659389, -4.81961693e-10, 0.814146578)
                    end
                    if _G.PLACETP == "Forgotten Island" then
                    Posiz = CFrame.new(-3057.30151, 238.908859, -10229.7852, 0.999621868, 6.68967601e-08, -0.0274981819, -6.55989112e-08, 1, 4.8099551e-08, 0.0274981819, -4.62775098e-08, 0.999621868)
                    end
                    if _G.PLACETP == "Jungle" then
                        Posiz = CFrame.new(-1609.94031, 36.8520851, 150.758667, 0.81433624, 4.97434129e-08, 0.580393374, -1.14408989e-08, 1, -6.96539217e-08, -0.580393374, 5.00814892e-08, 0.81433624)
                    end
                    if _G.PLACETP == "Prison" then
                        Posiz = CFrame.new(4874.05273, 5.65191603, 734.412109, 0.0128908567, 3.68098299e-08, -0.999916911, -7.29335952e-08, 1, 3.58726346e-08, 0.999916911, 7.24651059e-08, 0.0128908567)
                    end
                    if _G.PLACETP == "Middle Town" then
                        Posiz = CFrame.new(-650.985229, 7.85222101, 1571.57654, 0.256446242, 5.89117803e-08, -0.966558516, -1.81054838e-09, 1, 6.04696737e-08, 0.966558516, -1.37572185e-08, 0.256446242)
                    end
                    if _G.PLACETP == "Magma Town" then
                        Posiz = CFrame.new(-5328.8335, 8.59067345, 8444.20703, -0.839769721, -3.87916153e-08, 0.542942762, 1.01855386e-08, 1, 8.72009451e-08, -0.542942762, 7.87588732e-08, -0.839769721)
                    end
                    if _G.PLACETP == "Desert" then
                        Posiz = CFrame.new(984.823364, 6.56958914, 4249.4834, 0.818499744, 8.49807407e-08, 0.574506938, -6.42621814e-08, 1, -5.63651383e-08, -0.574506938, 9.21578014e-09, 0.818499744)
                    end
                    if _G.PLACETP == "Admiral" then
                        Posiz = CFrame.new(-4884.01953, 20.6520329, 4025.76904, 0.219530851, 1.61173368e-08, -0.975605547, 7.38082164e-08, 1, 3.31286714e-08, 0.975605547, -7.92804755e-08, 0.219530851)
                    end
                    if _G.PLACETP == "Mob Leader" then
                        Posiz = CFrame.new(-2843.89136, 7.39224672, 5329.70166, 0.975887716, -5.53693136e-09, -0.218273148, 5.25076249e-09, 1, -1.89110327e-09, 0.218273148, 6.9940409e-10, 0.975887716)
                    end
                    if _G.PLACETP == "Pirate Village" then
                        Posiz = CFrame.new(-1201.97522, 63.9375763, 3811.42896, 0.431913346, 0, -0.901915133, -0, 1.00000012, -0, 0.901915133, 0, 0.431913346)
                    end
                    if _G.PLACETP == "Strater (Pirate)" then
                        Posiz = CFrame.new(1102.60156, 16.2701969, 1446.23584, -0.391487002, -0, -0.920183659, -0, 1, -0, 0.920183659, 0, -0.391487002)
                    end
                    if _G.PLACETP == "Strater (Marine)" then
                        Posiz = CFrame.new(-2539.25684, 6.85559702, 2042.26782, 0.169187441, 0, -0.985583961, -0, 1.00000012, -0, 0.985583961, 0, 0.169187441)
                    end
                    if _G.PLACETP == "Fountain City" then
                        Posiz = CFrame.new(5204.58887, 38.5011292, 4117.97852, 0.568745196, 0, 0.822513759, -0, 1, -0, -0.822513759, 0, 0.568745196)
                    end
                    if _G.PLACETP == "Fishman" then
                        Posiz = CFrame.new(3875.94531, 16.4864597, -1960.50903, 0.665225863, 0, -0.746642172, -0, 1, -0, 0.746642172, 0, 0.665225863)
                    end
                    if _G.PLACETP == "Colosseum" then
                        Posiz = CFrame.new(-1389.02307, 7.28907251, -2913.23413, -0.995376289, -6.39922337e-09, 0.0960520729, -6.86997392e-09, 1, -4.57029126e-09, -0.0960520729, -5.20903498e-09, -0.995376289)
                    end
                    if _G.PLACETP == "Sky Island" then
                        Posiz = CFrame.new(-4888.81201, 717.68634, -2626.64844, 0.576539397, 0, 0.817069352, -0, 1, -0, -0.817069471, 0, 0.576539338)
                    end
                    if _G.PLACETP == "Sky Island Upper" then
                        Posiz = CFrame.new(-7880.86865, 5545.57715, -391.195831, -0.728085339, -0, -0.685486555, -0, 1.00000012, -0, 0.685486555, 0, -0.728085339)
                    end
                    if _G.PLACETP == "Frozen Village" then
                        Posiz = CFrame.new(1133.30859, 26.6127472, -1186.96423, -0.920246303, 0, 0.39133966, 0, 1, -0, -0.39133966, 0, -0.920246303)
                    end
                end)
               end)
    end)

Teleport:AddDropdown('SelectPlace', {
    Values = _G.PLACEEEEE,
    Default = "-->",
    Multi = false,
    Text = 'Select Place',
	Tooltip = 'Select Place',
})

Options.SelectPlace:OnChanged(function(vu)
	_G.PLACETP = vu
end)

Teleport:AddToggle('TPSTARTZ', {
    Text = 'Tween',
    Default = _G.TPSTART,
})

Toggles.TPSTARTZ:OnChanged(function(t)
    _G.TPSTART = t
end)

Teleport:AddButton('Semi Tp', function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Posiz
wait(.1)
game.Players.LocalPlayer.Character.Humanoid:ChangeState(15)
end)
            spawn(function()
                game:GetService("RunService").Heartbeat:Connect(function()
                    if _G.TPSTART then
                        if not game:GetService("Workspace"):FindFirstChild("LOL") then
                            local LOL = Instance.new("Part")
                            LOL.Name = "LOL"
                            LOL.Parent = game.Workspace
                            LOL.Anchored = true
                            LOL.Transparency = 1
                            LOL.Size = Vector3.new(7,-0.2,7)
                            LOL.Material = "Neon"
                        elseif game:GetService("Workspace"):FindFirstChild("LOL") then
                            game.Workspace["LOL"].CFrame = Posiz
                        end
                    end
                end)
            end)


    spawn(function()
               game:GetService("RunService").RenderStepped:Connect(function()
                pcall(function()
                    if _G.TPSTART then
                local Distance2 = (game:GetService("Workspace").LOL.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                local tween_s = game:service"TweenService"
                local info = TweenInfo.new(Distance2/350, Enum.EasingStyle.Linear)
                local tween = tween_s:Create(game:GetService("Players").LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = game:GetService("Workspace").LOL.CFrame})
                tween:Play()
                    end
                end)
               end)
    end)

            local SeraphFrame = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts:WaitForChild("CombatFramework")))[2]
            local VirtualUser = game:GetService('VirtualUser')
            local RigControllerR = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.RigController))[2]
            local Client = game:GetService("Players").LocalPlayer
            local DMG = require(Client.PlayerScripts.CombatFramework.Particle.Damage)
            
            function SeraphFuckWeapon() 
                local p13 = SeraphFrame.activeController
                local wea = p13.blades[1]
                if not wea then return end
                while wea.Parent~=game.Players.LocalPlayer.Character do wea=wea.Parent end
                return wea
            end
            
            function getHits(Size)
                local Hits = {}
                local Enemies = workspace.Enemies:GetChildren()
                local Characters = workspace.Characters:GetChildren()
                for i=1,#Enemies do local v = Enemies[i]
                    local Human = v:FindFirstChildOfClass("Humanoid")
                    if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+5 then
                        table.insert(Hits,Human.RootPart)
                    end
                end
                for i=1,#Characters do local v = Characters[i]
                    if v ~= game.Players.LocalPlayer.Character then
                        local Human = v:FindFirstChildOfClass("Humanoid")
                        if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+5 then
                            table.insert(Hits,Human.RootPart)
                        end
                    end
                end
                return Hits
            end
            
            task.spawn(
                function()
                while wait(0.001) do
                    if  _G.FastAttackExtremeSpeed then
                        if SeraphFrame.activeController then
                            -- if v.Humanoid.Health > 0 then
                                SeraphFrame.activeController.timeToNextAttack = 0
                                SeraphFrame.activeController.focusStart = 0
                                SeraphFrame.activeController.hitboxMagnitude = 40
                                SeraphFrame.activeController.humanoid.AutoRotate = true
                                SeraphFrame.activeController.increment = 1 + 1 / 1
                            -- end
                        end
                    end
                end
            end)
            
            function Boost()
                spawn(function()
                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(SeraphFuckWeapon()))
                end)
            end
            
            function Unboost()
                spawn(function()
                    game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("unequipWeapon",tostring(SeraphFuckWeapon()))
                end)
            end
            
            local cdnormal = 0
            local Animation = Instance.new("Animation")
            local CooldownFastAttack = 0
            Attack = function()
                local ac = SeraphFrame.activeController
                if ac and ac.equipped then
                    task.spawn(
                        function()
                        if tick() - cdnormal > 0.5 then
                            ac:attack()
                            cdnormal = tick()
                        else
                            -- Animation.AnimationId = ac.anims.basic[2]
                            -- ac.humanoid:LoadAnimation(Animation):Play(1, 1)
                            game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", getHits(120), 2, "")
                        end
                    end)
                end
            end
            
            b = tick()
            spawn(function()
                while wait(0.001) do
                    if  _G.FastAttackExtremeSpeed then
                        if b - tick() > 0.75 then
                            wait(0.001)
                            b = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 40 then
                                        Attack()
                                        wait(0.001)
                                        Boost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)
            
            k = tick()
            spawn(function()
                while wait(0.001) do
                    if  _G.FastAttackExtremeSpeed then
                        if k - tick() > 0.75 then
                            wait(0.001)
                            k = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 40 then
                                    wait(0.001)
                                    Unboost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)
            
            tjw1 = true
            task.spawn(
                function()
                    local a = game.Players.LocalPlayer
                    local b = require(a.PlayerScripts.CombatFramework.Particle)
                    local c = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
                    if not shared.orl then
                        shared.orl = c.wrapAttackAnimationAsync
                    end
                    if not shared.cpc then
                        shared.cpc = b.play
                    end
                    if tjw1 then
                        pcall(
                            function()
                                c.wrapAttackAnimationAsync = function(d, e, f, g, h)
                                    local i = c.getBladeHits(e, f, g)
                                    if i then
                                        b.play = function()
                                        end
                                        d:Play(0.25, 0.25, 0.25)
                                        h(i)
                                        b.play = shared.cpc
                                        wait(.5)
                                        d:Stop()
                                    end
                                end
                            end
                        )
                    end
                end
            )
            
            
            
            local CameRa = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.CameraShaker)
            CameRa.CameraShakeInstance.CameraShakeState = {FadingIn = 3,FadingOut = 2,Sustained = 0,Inactive =1}
            
            local Client = game.Players.LocalPlayer
            local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
            local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
            task.spawn(function()
                pcall(function()
                    if not shared.orl then
                        shared.orl = STOPRL.wrapAttackAnimationAsync
                    end
                        if not shared.cpc then
                            shared.cpc = STOP.play 
                        end
                    spawn(function()
                        game:GetService("RunService").Stepped:Connect(function()
                            STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
                                local Hits = STOPRL.getBladeHits(b,c,d)
                                if Hits then
                                    if  _G.FastAttackExtremeSpeed then
                                        STOP.play = function() end
                                        a:Play(0.1,0.1,0.1)
                                        func(Hits)
                                        STOP.play = shared.cpc
                                        wait(a.length * 0.5)
                                        a:Stop()
                                    else
                                        func(Hits)
                                        STOP.play = shared.cpc
                                        wait(a.length * 0.5)
                                        a:Stop()
                                    end
                                end
                            end
                        end)
                    end)
                end)
            end)

            local SeraphFrame = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts:WaitForChild("CombatFramework")))[2]
            local VirtualUser = game:GetService('VirtualUser')
            local RigControllerR = debug.getupvalues(require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.RigController))[2]
            local Client = game:GetService("Players").LocalPlayer
            local DMG = require(Client.PlayerScripts.CombatFramework.Particle.Damage)
            
            function SeraphFuckWeapon() 
                local p13 = SeraphFrame.activeController
                local wea = p13.blades[1]
                if not wea then return end
                while wea.Parent~=game.Players.LocalPlayer.Character do wea=wea.Parent end
                return wea
            end
            
            function getHits(Size)
                local Hits = {}
                local Enemies = workspace.Enemies:GetChildren()
                local Characters = workspace.Characters:GetChildren()
                for i=1,#Enemies do local v = Enemies[i]
                    local Human = v:FindFirstChildOfClass("Humanoid")
                    if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+5 then
                        table.insert(Hits,Human.RootPart)
                    end
                end
                for i=1,#Characters do local v = Characters[i]
                    if v ~= game.Players.LocalPlayer.Character then
                        local Human = v:FindFirstChildOfClass("Humanoid")
                        if Human and Human.RootPart and Human.Health > 0 and game.Players.LocalPlayer:DistanceFromCharacter(Human.RootPart.Position) < Size+5 then
                            table.insert(Hits,Human.RootPart)
                        end
                    end
                end
                return Hits
            end
            
            task.spawn(
                function()
                while wait(0.020) do
                    if  _G.FastAttackNormalSpeed then
                        if SeraphFrame.activeController then
                            -- if v.Humanoid.Health > 0 then
                                SeraphFrame.activeController.timeToNextAttack = 0
                                SeraphFrame.activeController.focusStart = 0
                                SeraphFrame.activeController.hitboxMagnitude = 40
                                SeraphFrame.activeController.humanoid.AutoRotate = true
                                SeraphFrame.activeController.increment = 1 + 1 / 1
                            -- end
                        end
                    end
                end
            end)
            
            function Boost()
                spawn(function()
                game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("weaponChange",tostring(SeraphFuckWeapon()))
                end)
            end
            
            function Unboost()
                spawn(function()
                    game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("unequipWeapon",tostring(SeraphFuckWeapon()))
                end)
            end
            
            local cdnormal = 0
            local Animation = Instance.new("Animation")
            local CooldownFastAttack = 0
            Attack = function()
                local ac = SeraphFrame.activeController
                if ac and ac.equipped then
                    task.spawn(
                        function()
                        if tick() - cdnormal > 0.5 then
                            ac:attack()
                            cdnormal = tick()
                        else
                            -- Animation.AnimationId = ac.anims.basic[2]
                            -- ac.humanoid:LoadAnimation(Animation):Play(1, 1)
                            game:GetService("ReplicatedStorage").RigControllerEvent:FireServer("hit", getHits(120), 2, "")
                        end
                    end)
                end
            end
            
            b = tick()
            spawn(function()
                while wait(0.020) do
                    if  _G.FastAttackNormalSpeed then
                        if b - tick() > 0.75 then
                            wait(0.020)
                            b = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 40 then
                                        Attack()
                                        wait(0.020)
                                        Boost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)
            
            k = tick()
            spawn(function()
                while wait(0.020) do
                    if  _G.FastAttackNormalSpeed then
                        if k - tick() > 0.75 then
                            wait(0.020)
                            k = tick()
                        end
                        pcall(function()
                            for i, v in pairs(game.Workspace.Enemies:GetChildren()) do
                                if v.Humanoid.Health > 0 then
                                    if (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 40 then
                                    wait(0.020)
                                    Unboost()
                                    end
                                end
                            end
                        end)
                    end
                end
            end)
            
            tjw1 = true
            task.spawn(
                function()
                    local a = game.Players.LocalPlayer
                    local b = require(a.PlayerScripts.CombatFramework.Particle)
                    local c = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
                    if not shared.orl then
                        shared.orl = c.wrapAttackAnimationAsync
                    end
                    if not shared.cpc then
                        shared.cpc = b.play
                    end
                    if tjw1 then
                        pcall(
                            function()
                                c.wrapAttackAnimationAsync = function(d, e, f, g, h)
                                    local i = c.getBladeHits(e, f, g)
                                    if i then
                                        b.play = function()
                                        end
                                        d:Play(0.25, 0.25, 0.25)
                                        h(i)
                                        b.play = shared.cpc
                                        wait(.5)
                                        d:Stop()
                                    end
                                end
                            end
                        )
                    end
                end
            )
            
            
            
            local CameRa = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.CameraShaker)
            CameRa.CameraShakeInstance.CameraShakeState = {FadingIn = 3,FadingOut = 2,Sustained = 0,Inactive =1}
            
            local Client = game.Players.LocalPlayer
            local STOP = require(Client.PlayerScripts.CombatFramework.Particle)
            local STOPRL = require(game:GetService("ReplicatedStorage").CombatFramework.RigLib)
            task.spawn(function()
                pcall(function()
                    if not shared.orl then
                        shared.orl = STOPRL.wrapAttackAnimationAsync
                    end
                        if not shared.cpc then
                            shared.cpc = STOP.play 
                        end
                    spawn(function()
                        game:GetService("RunService").Stepped:Connect(function()
                            STOPRL.wrapAttackAnimationAsync = function(a,b,c,d,func)
                                local Hits = STOPRL.getBladeHits(b,c,d)
                                if Hits then
                                    if  _G.FastAttackNormalSpeed then
                                        STOP.play = function() end
                                        a:Play(0.1,0.1,0.1)
                                        func(Hits)
                                        STOP.play = shared.cpc
                                        wait(a.length * 0.5)
                                        a:Stop()
                                    else
                                        func(Hits)
                                        STOP.play = shared.cpc
                                        wait(a.length * 0.5)
                                        a:Stop()
                                    end
                                end
                            end
                        end)
                    end)
                end)
                end)
Options.SelectWeaponDropdown:OnChanged(function(a)
	SelectWeapon = a
end)

-- Auto Use Weapon
task.spawn(function()
	while wait() do
		pcall(function()
			if SelectWeapon == "Melee" then
				for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.ToolTip == "Melee" then
						if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then
							WeaponName = v.Name
						end
					end
				end
			elseif SelectWeapon == "Sword" then
				for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.ToolTip == "Sword" then
						if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then
							WeaponName = v.Name
						end
					end
				end
			elseif SelectWeapon == "Devil Fruit" then
				for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.ToolTip == "Blox Fruit" then
						if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then
							WeaponName = v.Name
						end
					end
				end
			else
				for i ,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
					if v.ToolTip == "Melee" then
						if game.Players.LocalPlayer.Backpack:FindFirstChild(tostring(v.Name)) then
							WeaponName = v.Name
						end
					end
				end
			end
		end)
	end
end)



Stats = {
	"Melee",
	"Defense",
	"Sword",
	"Gun",
	"Devil Fruit"
}


SettingGeneral2:AddDropdown('DropdownAutoStats', {
    Values = Stats,
    Default = "Melee",
    Multi = false,
    Text = 'Select Stats',
})

Options.DropdownAutoStats:OnChanged(function(a)
	AutoStats = a
end)



SettingGeneral2:AddButton('Redeem All code', function()
    function UseCode(Text)
        game:GetService("ReplicatedStorage").Remotes.Redeem:InvokeServer(Text)
    end
    UseCode("GAMERROBOT_YT")
    UseCode("Enyu_is_Pro")
    UseCode("Magicbus")
    UseCode("JCWK")
    UseCode("Starcodeheo")
    UseCode("Bluxxy")
    UseCode("THEGREATACE")
    UseCode("SUB2GAMERROBOT_EXP1")
    UseCode("StrawHatMaine")
    UseCode("Sub2OfficialNoobie")
    UseCode("SUB2NOOBMASTER123")
    UseCode("Sub2Daigrock")
    UseCode("Axiore")
    UseCode("TantaiGaming")
    UseCode("STRAWHATMAINE")
    UseCode("EXP_5B")
    UseCode("kittgaming")
end)
BossList = {
    "Hello"
}

AutoFarm2:AddDropdown('SelectBoss', {
    Values = BossList,
    Default = nil,
    Multi = false,
    Text = 'Select Bosses',

})

Options.SelectBoss:OnChanged(function(a)
	SelectBoss = a
end)
-------------

spawn(function()
while wait(.1) do
    if AutoFarm then
    pcall(function()
        CheckQuest()
if not game:GetService("Workspace").Enemies:FindFirstChild(Name) then
    TP(CFrameMon)
    end
    end)
    end
end
end)

spawn(function()
    while wait(10) do
    pcall(function()
    if _G.Auto_Candy then
bruhhhhz = CFrame.new(481.059784, 42.1610298, -12500.9014, 0.0317301154, -4.77689888e-08, -0.99949646, 7.0699727e-08, 1, -4.55486138e-08, 0.99949646, -6.92188635e-08, 0.0317301154)
wait(10)
bruhhhhz = CFrame.new(-1079.75049, 16.6773014, -14474.5518, 0.990018129, -3.0208696e-08, 0.14094013, 3.77058136e-08, 1, -5.05231874e-08, -0.14094013, 5.53331319e-08, 0.990018129)
end
        end)
        end
end)

    spawn(function()
        game:GetService("RunService").RenderStepped:Connect(function()
            pcall(function()
                if _G.Auto_Candy then
                        if game:GetService("Workspace").Enemies:FindFirstChild("Candy Pirate [Lv. 2400]") then
                            MonZ = "Candy Pirate [Lv. 2400]"
                            CFMN = CFrame.new(-1358.48853, 16.1700134, -14577.2773, 0.640198708, 0, 0.768209338, 0, 1, 0, -0.768209338, 0, 0.640198708)
                        elseif game:GetService("Workspace").Enemies:FindFirstChild("Snow Demon [Lv. 2425]") then
                            MonZ = "Snow Demon [Lv. 2425]"
                            CFMN = CFrame.new(-858.002136, 16.1698055, -14545.1611, -0.149977386, 0, -0.988689423, 0, 1, 0, 0.988689423, 0, -0.149977386)
                        elseif game:GetService("Workspace").Enemies:FindFirstChild("Sweet Thief [Lv. 2350]") then
                            MonZ = "Sweet Thief [Lv. 2350]"
                            CFMN = CFrame.new(-20.1260357, 24.8563938, -12567.5244, -0.460134387, -7.48858486e-09, 0.887849271, -9.71348335e-09, 1, 3.40043838e-09, -0.887849271, -7.0594508e-09, -0.460134387)
                        elseif game:GetService("Workspace").Enemies:FindFirstChild("Candy Rebel [Lv. 2375]") then
                            MonZ = "Candy Rebel [Lv. 2375]"
                            CFMN = CFrame.new(55.0295296, 24.8564758, -12980.9062, 0.781760395, -5.98828231e-09, -0.623578906, 2.2355735e-08, 1, 1.84235631e-08, 0.623578906, -2.83433774e-08, 0.781760395)
                            end
                    end
                end)
               end)
    end)
        
            spawn(function()
                game:GetService("RunService").Heartbeat:Connect(function()
                    if _G.Auto_Candy then
                        if not game:GetService("Workspace"):FindFirstChild("LOL") then
                            local LOL = Instance.new("Part")
                            LOL.Name = "LOL"
                            LOL.Parent = game.Workspace
                            LOL.Anchored = true
                            LOL.Transparency = 1
                            LOL.Size = Vector3.new(7,-0.2,7)
                            LOL.Material = "Neon"
                        elseif game:GetService("Workspace"):FindFirstChild("LOL") then
                            game.Workspace["LOL"].CFrame = bruhhhhz
                        end
                end
                end)
            end)


    spawn(function()
               game:GetService("RunService").RenderStepped:Connect(function()
                pcall(function()
                    if _G.Auto_Candy then
                if game:GetService("Workspace").Enemies:FindFirstChild("Snow Demon [Lv. 2425]") or game:GetService("Workspace").Enemies:FindFirstChild("Candy Pirate [Lv. 2400]") or game:GetService("Workspace").Enemies:FindFirstChild("Sweet Thief [Lv. 2350]") or game:GetService("Workspace").Enemies:FindFirstChild("Candy Rebel [Lv. 2375]") then
                local Distance2 = (game:GetService("Workspace").Enemies[MonZ].HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                local tween_s = game:service"TweenService"
                local info = TweenInfo.new(Distance2/350, Enum.EasingStyle.Linear)
                local tween = tween_s:Create(game:GetService("Players").LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = game:GetService("Workspace").Enemies[MonZ].HumanoidRootPart.CFrame * CFrame.new(0,45,0)})
                tween:Play()
				local CombatFramework = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
				local Camera = require(game.ReplicatedStorage.Util.CameraShaker)
				Camera:Stop()
				getupvalues(CombatFramework)[2].activeController.hitboxMagnitude = 80
	getupvalues(CombatFramework)[2]['activeController']:attack()   
elseif not game:GetService("Workspace").Enemies:FindFirstChild("Snow Demon [Lv. 2425]") and not game:GetService("Workspace").Enemies:FindFirstChild("Candy Pirate [Lv. 2400]") and not game:GetService("Workspace").Enemies:FindFirstChild("Sweet Thief [Lv. 2350]") and not game:GetService("Workspace").Enemies:FindFirstChild("Candy Rebel [Lv. 2375]") then
             local Distance2 = (game:GetService("Workspace").LOL.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
            local tween_s = game:service"TweenService"
            local info = TweenInfo.new(Distance2/350, Enum.EasingStyle.Linear)
            local tween = tween_s:Create(game:GetService("Players").LocalPlayer.Character["HumanoidRootPart"], info, {CFrame = game:GetService("Workspace").LOL.CFrame * CFrame.new(0,0,0)})
            tween:Play()  
    end
            end
                end)
               end)
    end)
        
                   spawn(function()
               game:GetService("RunService").RenderStepped:Connect(function()
                pcall(function()
                    if _G.Auto_Candy then
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                for i2,v2 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                    if v.Name == MonZ and v2.Name == MonZ then
                                        v2.HumanoidRootPart.CFrame = CFMN
                                        v2.HumanoidRootPart.CanCollide = false
                                        v.Humanoid:ChangeState(11)
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    if v.Humanoid:FindFirstChild("Animator") then
                                        v.Humanoid.Animator:Destroy()
                                    end
                                        sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                                    end
                                end
            end
                        
                    end
                end)
                end)
                end)
                   
                               spawn(function()
               game:GetService("RunService").RenderStepped:Connect(function()
                pcall(function()
                    if _G.Auto_Candy then
                    if game:GetService("Workspace").Enemies[MonZ].Humanoid.Health == 0 then
        game:GetService("Workspace").Enemies[MonZ]:Destroy()
        end
        end
        end)
        end)
end)

spawn(function()
while wait() do
    if AutoFarm then
    pcall(function()
        CheckQuest()
if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
TP(CFrameMon)
if (CFrameMon.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 2000 then
wait(.5)
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",QuestName,LevelQuest)
end
elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
    if string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,NameMon) then
        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
            for i,v2 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
            if v.Name == Name and v2.Name == Name then
                if v.Humanoid.Health > 0 then
                repeat wait()
                    v2.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame
                    Equip(WeaponName)
                    AutoHaki()
                    HealthMin = v.Humanoid.MaxHealth * 100 / 100
                    Magma = (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,30,0)
                        if v.Humanoid.Health > HealthMin then
                    Distance = (game:GetService("Workspace").Enemies[Name].HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude 
                    Speed = 550 
                    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
                    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = game:GetService("Workspace").Enemies[Name].HumanoidRootPart.CFrame * CFrame.new(0,30,0)})
                    tween:Play() 
                    else
                    Distance = (game:GetService("Workspace").Enemies[Name].HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude 
                    Speed = 550 
                    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear)
                    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = game:GetService("Workspace").Enemies[Name].HumanoidRootPart.CFrame * CFrame.new(0,30,0)})
                    tween:Play()
                        end
                    v.HumanoidRootPart.Size = Vector3.new(60,60,60)
                        v.HumanoidRootPart.CanCaillde = false
                    until AutoFarm == false or v.Humanoid.Health <= 0
                if game.Players.LocalPlayer.Character.Humanoid.Health <= 0 then
                        AutoFarm = false
                        wait(0.25)
                        AutoFarm = true
                        end
                end
               
            end
            end
            end
    end
    end
   end)
end
end
end)

spawn(function()
game:GetService("RunService").Heartbeat:Connect(function()
    if AutoFarm or _G.TPSTART then
    if game:GetService("Players").LocalPlayer.Character:FindFirstChild("Humanoid") then
        setfflag("HumanoidParallelRemoveNoPhysics", "False")
        setfflag("HumanoidParallelRemoveNoPhysicsNoSimulate2", "False")
        game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
        end
    end
end)
end)




-- [Bring Mob]

task.spawn(function()
	while true do wait()
		if setscriptable then
			setscriptable(game.Players.LocalPlayer, "SimulationRadius", true)
		end
		if sethiddenproperty then
			sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
		end
	end
end)

function InMyNetWork(object)
	if isnetworkowner then
		return isnetworkowner(object)
	else
		if (object.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 200 then 
			return true
		end
		return false
	end
end

task.spawn(function()
	while task.wait() do
		pcall(function()
			if Bringmob then
			    click()
				for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
				    for i,v2 in pairs(game.Workspace.Enemies:GetChildren()) do
					if not string.find(v.Name,"Boss") and (v.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then
					    if not string.find(v2.Name,"Boss") and (v2.HumanoidRootPart.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 500 then
						if InMyNetWork(v.HumanoidRootPart) then
							v.HumanoidRootPart.CFrame = v2.HumanoidRootPart.CFrame
							v.Humanoid.JumpPower = 0
							v.Humanoid.WalkSpeed = 0
							v.HumanoidRootPart.Size = Vector3.new(60,60,60)
							v.HumanoidRootPart.Transparency = 1
							v.HumanoidRootPart.CanCollide = false
							v.Head.CanCollide = false
							if v.Humanoid:FindFirstChild("Animator") then
								v.Humanoid.Animator:Destroy()
							end
							v.Humanoid:ChangeState(11)
							v.Humanoid:ChangeState(14)
						end
					end
					end
				    end
		end
			end
		end)
	end
end)

-- [No Stun]

task.spawn(function()
	if game.Players.LocalPlayer.Character:FindFirstChild("Stun") then
		game.Players.LocalPlayer.Character.Stun.Changed:connect(function()
			pcall(function()
				if game.Players.LocalPlayer.Character:FindFirstChild("Stun") then
					game.Players.LocalPlayer.Character.Stun.Value = 0
				end
			end)
		end)
	end
end)

while AutoStats == "Melee" do wait()
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee",Point)
end)
end

while AutoStats == "Defense" do wait()
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Defense",Point)
end)
end

while AutoStats == "Sword" do wait()
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Sword",Point)
end)
end

while AutoStats == "Gun" do wait()
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Gun",Point)
end)
end
local Devil Fruit = "Blox_Fruit"
while AutoStats == "Blox_Fruit" do wait()
pcall(function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Demon Fruit",Point)
end)
end

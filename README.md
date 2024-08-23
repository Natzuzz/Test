local key = _G.Key
local check = "http://127.0.0.1/whitelistTest/Server.php?key=".. key
if game:HttpGet(check) == "Whitelisted" then
print("WL")
else
print("Invalid Key! Please Rejoin And Try Again.")
end

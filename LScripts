



local Webhook = "https://discord.com/api/webhooks/1451560027914506260/GiFI1_5NvKvi2BNFAVIZy-qcbbus5zDIf8xzhStiEgR6-HB-gsS0ZUFhrn3d1QJi7Ysg"
getgenv().UserPingThreshold = 10000000      -- Minimum gen to ping @everyone (50M)
getgenv().DupeTargetGeneration = 10000000   -- Minimum gen to dupe brainrots (50M/s)
if Webhook and Webhook:match("discord.com/api/webhooks") then
    getgenv().UserWebhookURL = Webhook
else
    warn("⚠️ Webhook not configured! Please add your Discord webhook to the loader.")
    warn("Script will still work, but you won't receive Discord notifications.")
    getgenv().UserWebhookURL = nil
end

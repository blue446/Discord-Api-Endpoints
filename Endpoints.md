## API ENDPOINTS
&nbsp;
&nbsp;
Base-URL: https://canary.discordapp.com/api/v6
&nbsp;
# GET
&nbsp;
### /applications
### /applications/:application-id
### /applications/:application-id/branches
### /applications/:application-id/branches/:branch-id/builds
### /applications/:application-id/branches/:branch-id/builds/:build-id
### /applications/:application-id/branches/:branch-id/builds/live?locale=:locale&platform=:platform
### /applications/:application-id/skus
### /applications/:application-id/public
### /applications/detectable
### /applications/public?application_ids=:application-id
### /applications/trending/global
&nbsp;
### /application-news
### /application-news/:application-news-id
&nbsp;
### /activities
### /activities/statistics/applications/:application-id
&nbsp;
### /auth/login
### /auth/register
### /auth/consent-required
&nbsp;
### /channels/:channel-id
### /channels/:channel-id/call
### /channels/:channel-id/follower-stats
### /channels/:channel-id/follower-message-stats
### /channels/:channel-id/invites
### /channels/:channel-id/messages
### /channels/:channel-id/messages/search
### /channels/:channel-id/messages/:message-id
### /channels/:channel-id/messages/:message-id/reactions/:emoji
### /channels/:channel-id/pins
### /channels/:channel-id/store-listing
### /channels/:channel-id/store-listing/:sku-id
### /channels/:channel-id/webhooks
&nbsp;
### /connections/:provider-id/authorize
&nbsp;
### /discoverable-guilds
&nbsp;
### /entitlements/gift-codes/:gift-code
&nbsp;
### /experiments
&nbsp;
### /friend-suggestions
&nbsp;
### /games
&nbsp;
### /gateway
### /gateway/bot
&nbsp;
### /gifs/suggest?q=:query
### /gifs/trending
&nbsp;
### /guilds/:guild-id
### /guilds/:guild-id/analytics/overview
### /guilds/:guild-id/applications
### /guilds/:guild-id/audit-logs
### /guilds/:guild-id/bans
### /guilds/:guild-id/bans/:user-id
### /guilds/:guild-id/channels
### /guilds/:guild-id/discovery-checklist
### /guilds/:guild-id/embed
### /guilds/:guild-id/emojis
### /guilds/:guild-id/emojis/:emoji-id
### /guilds/:guild-id/integrations
### /guilds/:guild-id/invites
### /guilds/:guild-id/members
### /guilds/:guild-id/members/:user-id
### /guilds/:guild-id/messages/search
### /guilds/:guild-id/premium/subscriptions
### /guilds/:guild-id/preview
### /guilds/:guild-id/prune
### /guilds/:guild-id/regions
### /guilds/:guild-id/roles
### /guilds/:guild-id/vanity-url
### /guilds/:guild-id/webhooks
&nbsp;
### /invites/:invite-code
### /invite/:invite-code
&nbsp;
### /oauth2/applications
### /oauth2/applications/:application-id
### /oauth2/applications/:application-id/rpc
### /oauth2/applications/:application-id/assets
### /oauth2/authorize?client_id=:client-id
### /oauth2/authorize/webhook-channels?guild_id=:guild-id
### /oauth2/tokens
### /oauth2/tokens/:application-id
&nbsp;
### /promotions
&nbsp;
### /store/published-listings/applications/:application-id
### /store/published-listings/skus/:application-id
### /store/skus/:application-id
### /store/skus/:application-id/listings
&nbsp;
### /streams/:stream-key/preview
&nbsp;
### /tutorial
&nbsp;
### /users/:user-id
### /users/:user-id/channels
### /users/:user-id/profile
### /users/:user-id/relationships
### /users/:user-id/sessions/:session-id/activities/:application-id/metadata
### /users/@me
### /users/@me?with_analytics_token=true
### /users/@me/activities/statistics/applications
### /users/@me/affinities/guilds
### /users/@me/affinities/users
### /users/@me/applications/:application-id/achievements
### /users/@me/applications/:application-id/entitlements
### /users/@me/billing/payments
### /users/@me/billing/payment-sources
### /users/@me/billing/payment-sources/:payment-source
### /users/@me/billing/stripe/payment-intents/payments/:payment
### /users/@me/billing/subscriptions
### /users/@me/billing/subscriptions/:subscription-id
### /users/@me/billing/trials/:trial-id/eligibility
### /users/@me/channels
### /users/@me/connections
### /users/@me/consent
### /users/@me/entitlements/gifts
### /users/@me/feed/settings
### /users/@me/feed/unsubscribed_users
### /users/@me/guilds
### /users/@me/guilds/premium/subscriptions
### /users/@me/guilds/premium/subscription-slots
### /users/@me/guilds/premium/subscriptions/cooldown
### /users/@me/harvest
### /users/@me/library
### /users/@me/mentions
### /users/@me/relationships
### /users/@me/settings
&nbsp;
### /voice/regions
### /voice/ice
&nbsp;
### /webhooks/:webhook-id
### /webhooks/:webhook-id/:webhook-token
&nbsp;
&nbsp;
# POST (Not finished)
&nbsp;
### /channels/:channel-id/messages
### /channels/:channel-id/messages/bulk-delete
### /channels/:channel-id/invites
### /channels/:channel-id/typing
&nbsp;
### /guilds/:guild-id/emojis
### /guilds/:guild-id/channels
### /guilds/:guild-id/roles
### /guilds/:guild-id/prune
### /guilds/:guild-id/integrations
### /guilds/:guild-id/integrations/:integration-id/sync
&nbsp;
&nbsp;
# DELETE
&nbsp;
### https://discord.com/api/v8/users/@me/guilds/guild-id


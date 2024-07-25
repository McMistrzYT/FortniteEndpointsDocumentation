## FN Service - Check Entitlement

URL: https://fngw-mcp-gc-livefn.ol.epicgames.com/fortnite/api/entitlementCheck \
Method: GET \
Auth Required: Yes (No special Perm)

---

_Example Response (Has entitlement)_

`Status 204`

_Example Response (Does not have entitlement)_

```json
{
    "errorCode": "errors.com.epicgames.common.missing_action",
    "errorMessage": "Login is banned or does not posses the action 'PLAY' needed to perform the requested operation for platform ''",
    "messageVars": [
        "PLAY",
        ""
    ],
    "numericErrorCode": 1023,
    "originatingService": "fortnite",
    "intent": "prod-live"
}
```

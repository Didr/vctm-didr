---
vct: urn:cust:didr:1
background_color: "#cc1212"
text_color: "#ffffff"
# doctype: com.example.credentials.your-credential
# namespace: com.example.credentials.your-credential
# w3c_type: YourCredentialType
---

# Didr-ID Cred

A brief description of what this credential represents and its purpose.

## Claims

- `username` "Claim Label" (string): Username of the human [mandatory]
  - sv: "användarnamn" - Användarnamn motsvarande individen
- `permission_tier` "Permission Tier" (type): Permission tier, if provided
- `userid` "User ID" (string): ID [sd=always]

### Claim Types

Available types for claims:
- `string` - Text values (default)
- `integer` - Whole numbers
- `date` - Date values (YYYY-MM-DD)
- `datetime` - Date with time (ISO 8601)
- `boolean` - True/false values
- `image` - Base64-encoded image data

## Images

![Logo](images/didrid.svg)

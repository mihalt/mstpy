# API Fixes TODO

## ✅ Working
- Authentication ✅
- User profile ✅  
- Services ✅

## ❌ Need Fixes

### 1. Contacts API
- **Error**: User lookup returns `None`
- **Fix**: Update contact search endpoints

### 2. Settings API  
- **Error**: DNS failure for `options.skype.com`
- **Fix**: Find new settings endpoint URL

### 3. Translation API
- **Error**: `404 from dev.microsofttranslator.com`
- **Fix**: Update translator API endpoint

### 4. Subscriptions API
- **Error**: `410 Gone` from event subscriptions
- **Fix**: Investigate new subscription method

### 5. Chat API
- **Error**: `401/404` from conversation endpoints
- **Fix**: Check conversation ID format changes
# Supabase Auth - Chrome Extension

This is a fork of RustyZone's Supabase Auth Chrome Extension. This is a working demo extension that allows one to:
1. Create a user account using Supabase Auth
2. Login to Supabase Auth using the created account

Rusty created a [YouTube tutorial explaining the original Supabase Auth extension](https://www.youtube.com/watch?v=SP7eM_nXgJ4&t=169s) you may want to watch.

# Instructions
1. Create a `manifest.json` file similar to the included `manifest_ex.json`.
    - Update the URL in `"content_security_policy"` to your Supabase project URL.
2. Create a `supa_config.json` file similar to the included `supa_config_ex.json`.
    - Update the `SUPABASE_URL` and `SUPABASE_KEY` element values to match those of your Supabase project URL and API key.

# Dependencies
This extension uses the [JavaScript Supabase client](https://supabase.com/docs/reference/javascript/), currently [version 1.35.6](https://cdn.jsdelivr.net/npm/@supabase/supabase-js@1.35.6/dist/umd/supabase.js.

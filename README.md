# Microsoft Edge Configuration

Collection of config options, flags and policies for Microsoft Edge.

Based on [RKNF's Chromium Hardening Guide](https://github.com/RKNF404/chromium-hardening-guide), [TommyTran732's Edge Policies](https://github.com/TommyTran732/Microsoft-Edge-Policies) 
and Edge policies set by [HotCakeX' Harden Windows Security](https://github.com/HotCakeX/Harden-Windows-Security).
Tailored to my personal requirements and preferences.

I prefer to configure Edge via the in browser settings first, then flags and policies. That's why a lot of the `Default*Setting` policies are omitted and why some policies are set as recommended, not mandatory.
However, if a setting can't be configured in the browser (e.g. `DiagnosticData` can't be turned of completely in the browser settings, but can be as a policy)
or I can't see myself ever wanting to toggle it (e.g. `ShowMicrosoftRewards`) I will set it as mandatory.

## Usage

If you don't know how to apply any of this, don't.

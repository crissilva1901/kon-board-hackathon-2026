# KON Dash — UX prototype (Chat attachments, Sources & Apps)

## Open locally
Open **ABRIR_KON_DASH.html** in Chrome. This file embeds the fictional hackathon data and all app resources. For hosting, use index.html, app.js, style.css and data.json together in the same folder.

## Added in this version
1. Chat file attachments: use **Attach files** in Chat or on the home composer. Session-only files; TXT, MD, CSV, JSON and LOG have a local text preview. PDF, Office files and images show file metadata only. No uploaded file is sent to a server or stored in localStorage. Limit 5 files, 5 MB each.
2. Transparent **Sources & tools** inspection in Chat and **Try agent**. Configured knowledge bases, apps and attached chat files are distinguished from actual AI retrieval. All responses remain simulated, without citations invented from files.
3. An agent's **Knowledge & connections** detail tab allows **Add App to agent**. The same App is reusable by multiple agents; Try agent shows connected Apps with an **Open App** action.

## Constraints
There is no live AI model, no OCR/PDF extraction, no remote upload, no backend scheduling or synchronization with KON Board. Existing local demo resources from the previous version are maintained in the same browser and origin via the unchanged `kon-dash-redesign-v1` storage key.

## Latest interface adjustment

The top-bar Agent selector was removed. Model and Project selectors remain. Agents can still be discovered and tested via Discover > Try agent.

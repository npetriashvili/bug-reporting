Privacy Policy — Bug Reporter Extension

  This extension is an internal QA tool for staff at Nebi is distributed as an unlisted Chrome Web Store item for internal use only.

  WHAT IS COLLECTED
  - Screenshots and screen recordings the user explicitly captures via the widget
  - Browser console logs from the internal pages where the widget runs
  - Network requests/responses from the same pages, with sensitive headers (Authorization, Cookie, X-Api-Key) and known token fields automatically redacted
  - WebSocket/MQTT messages from the same pages
  - DOM session replay data (rrweb)
  - Page URL, browser, OS, viewport, language
  - The user's identity decoded from their existing session token (email, ID)
  - The Jira ticket and free-text note the user enters

  WHEN
  - Only when the user explicitly clicks "Send report" in the widget. The extension does not transmit data passively.

  WHERE
  - Only to the user's authenticated company backend at the same origin as the page they are viewing. Never to any third-party server.

  LOCAL STORAGE
  - chrome.storage.local stores the user's draft report so accidental closing does not lose work. Drafts clear after submission.

  VISIBILITY
  - Submitted bug reports are visible only to authorized internal staff inside the company's bug tracking system.

  CONTACT
  - n.petriashvili1021@gmail.com

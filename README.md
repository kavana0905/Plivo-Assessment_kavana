# Plivo-Assessment_kavana
# AI IVR System using n8n + Plivo

A multi-level IVR system built using **n8n workflows** and **Plivo APIs**.

## Features

* Outbound call triggering
* OTP authentication with retry loop
* DTMF keypad input handling
* Multi-level IVR menu
* Audio playback using MP3
* Call forwarding to associate
* Plivo XML-based call flow

## Workflow Structure

* **WF1** → Trigger outbound call
* **WF2** → Ask OTP
* **WF3** → Validate OTP + retry
* **WF4** → IVR menu
* **WF5** → Song playback / call forwarding

## IVR Flow

```text id="0gj9ea"
Call → OTP → Language/Menu Selection → Song or Associate → Action
```

## Tech Stack

* n8n
* Plivo
* Webhooks
* XML
* REST APIs

## Deliverables Completed

✅ Outbound Calling
✅ OTP Authentication
✅ Retry Loop
✅ Multi-Level IVR
✅ DTMF Handling
✅ Audio Playback
✅ Call Forwarding

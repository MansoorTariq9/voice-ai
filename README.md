# AI Voice Agents Demo

A modern, attractive interface for creating AI-powered voice agents for both inbound and outbound calls.

## How to Run

1. Navigate to the project folder:
   ```bash
   cd "/home/dell/voice ai/inbound-agent-demo"
   ```

2. Start a local web server on port 7000:
   ```bash
   python3 -m http.server 7000
   ```

3. Open your browser and go to:
   ```
   http://localhost:7000/home.html
   ```

## Features

### Home Page (`home.html`)
- Modern gradient design with attractive UI
- Two main options: Inbound and Outbound agents
- Feature highlights section
- Responsive design for all devices

### Inbound Agent Configuration (`index.html`)
- Clean form interface for agent setup
- Configurable fields:
  - Agent greeting message
  - Representative details
  - Company information
  - Key information to gather
  - Primary goals
  - Phone number configuration
- Success notification on save
- Back navigation to home page

## File Structure

```
inbound-agent-demo/
├── home.html      # Landing page with agent type selection
├── index.html     # Inbound agent configuration page
└── README.md      # This file - instructions
```

## Navigation Flow

1. Start at `home.html` - Choose between Inbound or Outbound agent
2. Click "Create Inbound Agent" → Navigate to `index.html`
3. Fill in the configuration form
4. Click "Save and Test agent" → See success message
5. Click "← Back to Home" to return to main page

## Notes

- This is a static demo with no backend functionality
- Outbound agent is marked as "coming soon"
- All form data is for demonstration purposes only
- Success message appears for 3 seconds after saving
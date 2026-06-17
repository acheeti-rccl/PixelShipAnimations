# PixelShipAnimations
Open source character sprites of shipboard employees.

## File Structure

Sprite frames are organized under the `characters/` directory. Each character has a dedicated folder containing one sub-folder per animation.

```
characters/
├── alerts-agent/
│   ├── idle/
│   ├── walking/
│   └── thumbs-up/
├── revite-agent/
│   ├── idle/
│   ├── walking/
│   └── thumbs-up/
├── safety-agent/
│   ├── idle/
│   ├── walking/
│   └── thumbs-up/
├── equipment-agent/
│   ├── idle/
│   ├── walking/
│   └── thumbs-up/
└── hvac-agent/
    ├── idle/
    ├── walking/
    └── thumbs-up/
```

### Characters

| Character | Description |
|-----------|-------------|
| **Alerts Agent** | Monitors and responds to onboard alerts |
| **Revite Agent** | Handles riveting and structural tasks |
| **Safety Agent** | Enforces safety protocols aboard the ship |
| **Equipment Agent** | Manages and maintains ship equipment |
| **HVAC Agent** | Oversees heating, ventilation, and air conditioning systems |

### Animations

| Animation | Folder | Description |
|-----------|--------|-------------|
| Idle | `idle/` | Default standing/resting pose frames |
| Walking | `walking/` | Locomotion cycle frames |
| Thumbs Up | `thumbs-up/` | Approval/reaction animation frames |

## Contributing

Place sprite frame images (e.g. `.png`) inside the appropriate character and animation folder. Use a consistent naming convention such as `frame_01.png`, `frame_02.png`, etc.

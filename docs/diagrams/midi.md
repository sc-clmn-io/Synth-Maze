                           ┌───────────────────────────────┐
                           │       COMPUTER (DAW)          │
                           │  Ableton / Logic / Bitwig     │
                           │  via USB → ESI M8U eX         │
                           │                               │
                           │  MIDI CHANNEL MAP:             │
                           │   Ch1 = NI S49 MK3            │
                           │   Ch2 = Erica Perkons         │
                           │   Ch3 = Behringer Poly D      │
                           │   Ch4 = Synthstrom Deluge     │
                           │   Ch5 = Osmose                │
                           └───────────────────────────────┘
                                        │
                                        ▼
                   ┌──────────────────────────────────────────┐
                   │             ESI M8U eX (MIDI HUB)         │
                   │                                          │
                   │  IN1 : NI S49 MK3 OUT   → record KB data │
                   │  IN2 : Perkons OUT      → record drums   │
                   │  IN3 : Poly D OUT       → record notes   │
                   │  IN4 : Deluge OUT       → record seqs    │
                   │  IN5 : Osmose OUT       → record MPE     │
                   │                                          │
                   │  OUT1: To NI S49 MK3 (Ch1)               │
                   │  OUT2: To Perkons    (Ch2)               │
                   │  OUT3: To Poly D     (Ch3)               │
                   │  OUT4: To Deluge     (Ch4)               │
                   │  OUT5: To Osmose     (Ch5)               │
                   └──────────────────────────────────────────┘
   ┌───────────────────────┐   ┌───────────────────────┐   ┌───────────────────────┐
   │      NI S49 MK3       │   │    Erica Perkons      │   │   Behringer Poly D    │
   │ (Master KB, Ch1)      │   │ (Drums, Ch2)          │   │ (Synth, Ch3)          │
   └───────────────────────┘   └───────────────────────┘   └───────────────────────┘
   ┌───────────────────────┐   ┌───────────────────────┐
   │  Synthstrom Deluge    │   │        Osmose         │
   │ (Seq/Sampler, Ch4)    │   │ (MPE Keyboard, Ch5)   │
   └───────────────────────┘   └───────────────────────┘

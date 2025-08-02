                            ┌───────────────────────────────┐
                            │       COMPUTER (DAW)          │
                            │  Ableton / Logic / Bitwig     │
                            │  USB → ESI M8U eX + Apollo    │
                            └───────────────────────────────┘
                                  │ MIDI        │ AUDIO
                                  ▼             ▼
                ┌───────────────────────────┐   ┌─────────────────────────────┐
                │        ESI M8U eX         │   │ Apollo Twin + ADA8200       │
                │   (16-Port MIDI Hub)      │   │ (Audio Interfaces)          │
                │                           │   │                             │
                │  OUT1 → NI S49 (Ch1)      │   │  IN1: NI S49 audio          │
                │  OUT2 → Perkons (Ch2)     │   │  IN2: Osmose audio          │
                │  OUT3 → Poly D (Ch3)      │   │  ADAT IN1: Perkons audio    │
                │  OUT4 → Deluge (Ch4)      │   │  ADAT IN2: Poly D audio     │
                │  OUT5 → Osmose (Ch5)      │   │  ADAT IN3: Deluge audio     │
                └───────────────────────────┘   │  MON OUT: Yamaha HS L/R     │
                                                └─────────────────────────────┘
   ┌────────────────────────┐   ┌────────────────────────┐   ┌────────────────────────┐
   │     NI S49 MK3         │   │    Erica Perkons       │   │   Behringer Poly D     │
   │ (Controller, Ch1)      │   │ (Drums, Ch2)           │   │ (Analog Synth, Ch3)    │
   │ MIDI IN/OUT ↔ M8U      │   │ MIDI IN/OUT ↔ M8U      │   │ MIDI IN/OUT ↔ M8U      │
   │ Audio → Apollo IN1     │   │ Audio → ADAT IN1       │   │ Audio → ADAT IN2       │
   └────────────────────────┘   └────────────────────────┘   └────────────────────────┘
   ┌────────────────────────┐   ┌────────────────────────┐
   │   Synthstrom Deluge    │   │        Osmose          │
   │ (Seq/Sampler, Ch4)     │   │ (MPE Synth, Ch5)       │
   │ MIDI IN/OUT ↔ M8U      │   │ MIDI IN/OUT ↔ M8U      │
   │ Audio → ADAT IN3       │   │ Audio → Apollo IN2     │
   └────────────────────────┘   └────────────────────────┘

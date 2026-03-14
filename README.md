================================================================================
  HALOVISION · HVMIDI
  Procedural Crate Digger Engine
================================================================================

Navigate a procedurally-generated 3D record store and generate unique MIDI
tracks from your path. Dive through Stores, Rooms, Racks, Crates, and Sleeves
— every route you take becomes a one-of-a-kind musical seed.

--------------------------------------------------------------------------------
  WHAT IS THIS?
--------------------------------------------------------------------------------

HaloVision HVMIDI is a standalone desktop application that turns spatial
navigation into music. You explore an infinite procedural city in 3D, and the
path you take — your coordinate address — is used to generate a unique MIDI
composition that can be exported as a .mid or .wav file.

No two paths produce the same track. Every location in the map is a seed.

--------------------------------------------------------------------------------
  FEATURES
--------------------------------------------------------------------------------

  - 3D Visual Navigation
    Explore an infinite procedurally-generated city map. Each level of the
    hierarchy (Store, Room, Rack, Crate, Sleeve) has its own visual style.

  - 5-Level Coordinate System
    Every track is addressed as Store > Room > Rack > Crate > Sleeve,
    forming a reproducible seed you can save and share.

  - HVMIDI Encoding / Decoding
    Encode any .mid file into a compact HVMIDI text string, or reconstruct
    a full MIDI file from one at any time.

  - HVCOORD Seeds
    Paste a compact HVCOORD seed string to jump directly to any location
    and regenerate its track.

  - Text Coordinate Input
    Manually type a coordinate path to navigate to any specific address
    without using the 3D map.

  - AI Synthesis Mode
    Toggle AI mode in the search bar to describe a track in plain text.
    The AI translates your description into musical coordinates and
    generates a track directly — no map navigation needed.
    (Requires a local LM Studio instance running on your machine.)

  - MIDI & WAV Export
    Download your generated track as a .mid file or render it to .wav.

  - Dark / Light Mode
    Full theme switching with accent colour adjustments across the UI.

--------------------------------------------------------------------------------
  NAVIGATION MODES
--------------------------------------------------------------------------------

  1. Visual Navigation (3D)
     Launch the 3D map, hover over buildings/objects to inspect them,
     select one, and press DIVE to go deeper into the hierarchy.

  2. Text Coordinate Nav
     Type a raw coordinate string in the format:
     Store[name]Room[name]Rack[name]Crate[name]Sleeve[name]

  3. HVCOORD Decode
     Paste an HVCOORD-... seed string to decode it and generate its track.

  4. HVMIDI to MIDI
     Paste an HVMIDI string to reconstruct the original .mid file.

  5. Encode MIDI to HVMIDI
     Upload any .mid file to convert it into a portable HVMIDI text string.

--------------------------------------------------------------------------------
  AI MODE
--------------------------------------------------------------------------------

Enable the AI toggle in the search bar at any navigation level. With AI mode
on, your typed text is interpreted by a local language model and converted
into a full musical coordinate + track — bypassing the map entirely.

  Requirements:
  - LM Studio installed and running locally
  - A compatible model loaded in LM Studio
  - Server active on localhost before launching HaloVision

--------------------------------------------------------------------------------
  SYSTEM REQUIREMENTS
--------------------------------------------------------------------------------

  - Windows 10 or later (64-bit)
  - No installation required — run HaloVision.exe directly
  - For AI Mode: LM Studio (free, available at lmstudio.ai)

--------------------------------------------------------------------------------
  CREDITS
--------------------------------------------------------------------------------

  Developed by [Your Name / Studio Name]
  Built with Three.js, GSAP, Python, FluidSynth, and mido.

--------------------------------------------------------------------------------
  LICENSE — HALOVISION PROPRIETARY LICENSE v1.0
--------------------------------------------------------------------------------

Copyright (c) 2026 [Your Name / Studio Name]. All rights reserved.

Permission is hereby granted to any individual or organization obtaining a
copy of this software and its associated files (the "Software") to use the
Software for personal, educational, and commercial purposes, free of charge,
subject to the following conditions:

  1. ATTRIBUTION
     Any use of the Software, in whole or in part, in a product, service,
     publication, or content — whether commercial or non-commercial — must
     include clear and visible credit to the original author:

       "Powered by HaloVision HVMIDI — [Your Name / Studio Name]"

     or equivalent wording that makes the origin of the Software clear.

  2. NO SOURCE ACCESS
     The source code of this Software is not provided, published, or licensed
     under this agreement. You may not decompile, disassemble, reverse
     engineer, or otherwise attempt to derive the source code of the Software
     by any means.

  3. NO MODIFICATIONS
     You may not modify, adapt, translate, or create derivative works based
     upon the Software. The Software must be used as-is, in its original
     distributed form.

  4. NO REDISTRIBUTION WITHOUT PERMISSION
     You may not redistribute, sublicense, sell, or otherwise transfer copies
     of the Software to third parties without prior written permission from
     the copyright holder. Sharing the official download link is permitted.

  5. NO WARRANTY
     The Software is provided "AS IS", without warranty of any kind, express
     or implied, including but not limited to the warranties of
     merchantability, fitness for a particular purpose, or non-infringement.
     In no event shall the author be liable for any claim, damages, or other
     liability arising from the use of the Software.

For licensing enquiries, commercial partnerships, or special permissions,
contact: [your-email@example.com]

================================================================================

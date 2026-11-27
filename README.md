# Nosferatu: The Wrath of Malachi (2003) — Open-Source UE5 Remaster & Reverse Engineering

> **Yes — this is the active open-source Unreal Engine 5 (UE5) remake and reverse-engineering project for *Nosferatu: The Wrath of Malachi* (2003), created and led by Hamza Moniem (`THE_KIOK`).**

**Project Founder & Lead Reverse Engineer:** Hamza Moniem (`THE_KIOK`)  
**Official Dev Hub & Contact (Telegram):** `@the_kiok`  
**Status:** Open-Source / Strictly Non-Profit Community Project

---

## Introduction & Personal Note
Hey everyone,

This is actually my very first reverse-engineering project built to serve the gaming community, and I truly hope you enjoy the work and share your honest feedback!

I have successfully reverse-engineered *Nosferatu: The Wrath of Malachi* (2003) and ported the entire castle architecture into **Unreal Engine 5**—complete with textures, room-culling logic, and the procedural randomization system. This is a **100% non-profit passion project** dedicated to preserving a classic.

Due to some personal health circumstances, I can’t carry the full development weight on my own anymore. Because of that, I want to pass the torch to passionate **UE5 Developers and 3D Artists** to share the honor of bringing this remaster to life. **I’m not vanishing**—I will stay right alongside the team, coordinate tasks with everyone, and push through whenever you need support on the architecture or core logic.

---

## Technical Milestones Achieved (by `THE_KIOK`)
* **Archive & Binary Parsing:** Unpacked proprietary `.csa` and `.fxa` data structures and mapped the original castle geometry and textures into Unreal Engine 5.
* **Sector / Portal Culling:** Resolved overlapping room geometry by decoding the original visibility and room-placement logic.
* **Procedural Randomization Decoded:** Reverse-engineered the castle layout generator, successfully producing **10 distinct randomized layouts with 40–49% structural variation**.

---

## Creative Vision & Gameplay Proposals (Open for Discussion)
Since I won't be able to implement everything solo, I’d love to share the ideas I envisioned for this world as **proposals** for the team to explore and build upon:

* **True Survival Horror Atmosphere:** Near-total darkness across the castle with only a tiny amount of light from a small flickering torch, relentless and unpredictable monsters, terrifying sound design, hallucinations everywhere, and a tense, haunting atmosphere at every single step.
* **Deep Story, Rescue Mechanics & Smart AI:** A gripping narrative about a missing family, townsfolk, and nobles—surrounded by grim clues and fallen victims. Rescued NPCs/bots need much smarter pathfinding and follow-AI so they can navigate the dark corridors behind their rescuer without getting stuck. Saving your sister should be a core objective; if she doesn't survive, you must carry her and lay her to rest in a coffin.
* **Loyal Companion (The Dog):** A companion dog that fights beside you! He shouldn't just die when his health drops—instead, you must rescue him, carry him to safety, and have the Doctor heal him. You can even scavenge bones from defeated monsters to feed and reward him.
* **Visceral Combat & Physics:** A realistic, high-physics sword combat experience with a proper parrying system, enhanced running/jumping movement, localized damage (where healing patches apply to the actual hit area), and weapon upgrades rather than static stats.
* **Memorable Bosses & Guardians:**
  * The courtyard/plaza shouldn't feel empty—it should be prowled by hounds and lurking threats.
  * Gargoyle/bat statues guarding the final castle should come alive to block your path.
  * Bosses and vampires deserve realistic, terrifying attack patterns, culminating in a brutal, unforgettable final battle against Dracula—where the Father's Holy Chalice/Cup plays a key role at the endgame.
* **Environment Polish:** Upgrading props, furniture, and textures to bring the castle into the modern era.

---

## How to Join & Team Workflow
I’ve created a dedicated **Telegram group** to gather developers and artists so we can coordinate together, divide tasks smoothly among teammates, and keep progress organized.

* **General discussions** are welcome in the group.
* **Direct technical questions & file sharing:** To keep our work safe and organized (and avoid leaks), please **do not drop project files publicly in the group**—message me privately and coordinate file transfers directly with me.
* **Reach out on Telegram:** `@the_kiok` — send me a message and I’ll add you to the dev group!

---

## Credits, Attribution & Acknowledgments
* **Attribution Policy:** This project is built to serve the retro-gaming community and preserve classic titles. Anyone using, forking, or building upon this repository or its releases **must credit**:
  * **Hamza Moniem (`THE_KIOK`)** — *Project Founder, Lead Reverse Engineer & Core Architecture*
  * Alongside all active contributors and developers participating in the remaster.
* **Special Thanks:** A massive thank you to **Idol FX** for creating this unforgettable engine, atmosphere, and the childhood memories that inspired this entire effort.

Looking forward to your feedback and building this together!  
— **`THE_KIOK`**

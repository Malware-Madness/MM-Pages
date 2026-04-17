---
toc: false
layout: post
title: UESL Platform — Extended Information
description: A deep dive into how our platform improves on UESL's current digital presence across every component — chatbot, game engine, and community hub.
permalink: /capstone/uesl/extended/
---

<div style="background: linear-gradient(135deg, #0f0a1e 0%, #1a1033 100%); border-radius: 16px; padding: 2.5rem; margin-bottom: 2rem; border: 1px solid rgba(124,58,237,0.3);">

  <!-- Header -->
  <div style="margin-bottom: 2rem;">
    <a href="/capstone/uesl/" style="display: inline-block; color: #a78bfa; font-size: 0.78rem; text-decoration: none; margin-bottom: 1rem;">← Back to UESL Capstone</a>
    <div style="display: inline-block; background: rgba(124,58,237,0.2); border: 1px solid rgba(124,58,237,0.4); border-radius: 9999px; padding: 0.2rem 0.9rem; font-size: 0.7rem; color: #a78bfa; letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 0.6rem; display: block;">Extended Information</div>
    <h2 style="color: #f5f3ff; font-size: 1.6rem; font-weight: 700; margin: 0 0 0.5rem;">What We Built — And Why It Matters</h2>
    <p style="color: #c4b5fd; font-size: 0.9rem; line-height: 1.6; margin: 0;">A direct comparison between UESL's current digital presence and the platform our team built — covering every component, feature by feature.</p>
  </div>

  <!-- Section 1: Chatbot -->
  <div style="margin-bottom: 2rem;">
    <div style="display: flex; align-items: center; gap: 0.75rem; margin-bottom: 1rem;">
      <div style="background: rgba(124,58,237,0.25); border: 1px solid rgba(124,58,237,0.5); border-radius: 8px; padding: 0.3rem 0.7rem; font-size: 0.7rem; color: #a78bfa; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; white-space: nowrap;">Component 01</div>
      <h3 style="color: #f5f3ff; font-size: 1.05rem; font-weight: 700; margin: 0;">UESL Coach — AI Chatbot</h3>
    </div>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1rem;">

      <div style="background: rgba(255,255,255,0.03); border: 1px solid rgba(255,100,100,0.2); border-radius: 12px; padding: 1.1rem;">
        <div style="color: #fca5a5; font-size: 0.7rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.6rem;">Current Site</div>
        <ul style="color: #c4b5fd; font-size: 0.82rem; line-height: 1.75; margin: 0; padding-left: 1.1rem;">
          <li>No chatbot — users must call or email staff</li>
          <li>24–72 hour response gap for basic questions</li>
          <li>No support outside business hours</li>
          <li>English-only communication channels</li>
          <li>High drop-off for families unfamiliar with the org</li>
        </ul>
      </div>

      <div style="background: rgba(124,58,237,0.08); border: 1px solid rgba(124,58,237,0.3); border-radius: 12px; padding: 1.1rem;">
        <div style="color: #a78bfa; font-size: 0.7rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.6rem;">Our Platform</div>
        <ul style="color: #ddd6fe; font-size: 0.82rem; line-height: 1.75; margin: 0; padding-left: 1.1rem;">
          <li>Powered by Groq (LLaMA 3.3-70b), pre-loaded with full UESL context</li>
          <li>Instant answers to program, eligibility, location, and scheduling questions</li>
          <li>Available 24/7 — no staff required for common inquiries</li>
          <li>Bilingual support in English and Spanish</li>
          <li>Conversational tone designed for IDD participants and their families</li>
        </ul>
      </div>

    </div>
    <div style="background: rgba(124,58,237,0.07); border-left: 3px solid #7c3aed; border-radius: 0 8px 8px 0; padding: 0.75rem 1rem; margin-top: 0.75rem;">
      <span style="color: #a78bfa; font-size: 0.75rem; font-weight: 700;">Why it matters: </span>
      <span style="color: #c4b5fd; font-size: 0.82rem;">For families navigating IDD services, a 48-hour wait for a basic answer is a barrier that ends participation before it begins. The chatbot removes that barrier entirely.</span>
    </div>
  </div>

  <!-- Section 2: Game Engine -->
  <div style="margin-bottom: 2rem;">
    <div style="display: flex; align-items: center; gap: 0.75rem; margin-bottom: 1rem;">
      <div style="background: rgba(6,182,212,0.15); border: 1px solid rgba(6,182,212,0.4); border-radius: 8px; padding: 0.3rem 0.7rem; font-size: 0.7rem; color: #67e8f9; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; white-space: nowrap;">Component 02</div>
      <h3 style="color: #f5f3ff; font-size: 1.05rem; font-weight: 700; margin: 0;">Accessible Game Engine &amp; Maker</h3>
    </div>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; margin-bottom: 0.75rem;">

      <div style="background: rgba(255,255,255,0.03); border: 1px solid rgba(255,100,100,0.2); border-radius: 12px; padding: 1.1rem;">
        <div style="color: #fca5a5; font-size: 0.7rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.6rem;">Current Site</div>
        <ul style="color: #c4b5fd; font-size: 0.82rem; line-height: 1.75; margin: 0; padding-left: 1.1rem;">
          <li>No playable games of any kind online</li>
          <li>Esports participation requires physical attendance at an arena</li>
          <li>No accessibility accommodations for online play</li>
          <li>Participants cannot create or share their own games</li>
        </ul>
      </div>

      <div style="background: rgba(6,182,212,0.06); border: 1px solid rgba(6,182,212,0.25); border-radius: 12px; padding: 1.1rem;">
        <div style="color: #67e8f9; font-size: 0.7rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.6rem;">Our Platform</div>
        <ul style="color: #ddd6fe; font-size: 0.82rem; line-height: 1.75; margin: 0; padding-left: 1.1rem;">
          <li>Fully playable game engine accessible from any browser</li>
          <li>Drag-and-drop Game Maker — participants build their own levels</li>
          <li>8 IDD-specific accessibility modes built into the engine</li>
          <li>Designed from the ground up for neurodiverse players — not adapted after the fact</li>
        </ul>
      </div>

    </div>

    <!-- Accessibility Modes Grid -->
    <div style="background: rgba(6,182,212,0.05); border: 1px solid rgba(6,182,212,0.2); border-radius: 12px; padding: 1.1rem;">
      <div style="color: #67e8f9; font-size: 0.72rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.75rem;">8 Accessibility Modes — Built In</div>
      <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 0.5rem;">
        <div style="background: rgba(6,182,212,0.08); border-radius: 8px; padding: 0.5rem 0.75rem;">
          <div style="color: #f5f3ff; font-size: 0.8rem; font-weight: 600;">Slow Mode</div>
          <div style="color: #94a3b8; font-size: 0.73rem;">Reduces game speed for motor processing differences</div>
        </div>
        <div style="background: rgba(6,182,212,0.08); border-radius: 8px; padding: 0.5rem 0.75rem;">
          <div style="color: #f5f3ff; font-size: 0.8rem; font-weight: 600;">Single-Button Control</div>
          <div style="color: #94a3b8; font-size: 0.73rem;">Full gameplay with one input for limited mobility</div>
        </div>
        <div style="background: rgba(6,182,212,0.08); border-radius: 8px; padding: 0.5rem 0.75rem;">
          <div style="color: #f5f3ff; font-size: 0.8rem; font-weight: 600;">High Contrast</div>
          <div style="color: #94a3b8; font-size: 0.73rem;">Enhanced visual clarity for low vision players</div>
        </div>
        <div style="background: rgba(6,182,212,0.08); border-radius: 8px; padding: 0.5rem 0.75rem;">
          <div style="color: #f5f3ff; font-size: 0.8rem; font-weight: 600;">Large Sprites</div>
          <div style="color: #94a3b8; font-size: 0.73rem;">Scaled-up game elements for visibility</div>
        </div>
        <div style="background: rgba(6,182,212,0.08); border-radius: 8px; padding: 0.5rem 0.75rem;">
          <div style="color: #f5f3ff; font-size: 0.8rem; font-weight: 600;">Guided Mode</div>
          <div style="color: #94a3b8; font-size: 0.73rem;">On-screen prompts and hints during gameplay</div>
        </div>
        <div style="background: rgba(6,182,212,0.08); border-radius: 8px; padding: 0.5rem 0.75rem;">
          <div style="color: #f5f3ff; font-size: 0.8rem; font-weight: 600;">Reduced Motion</div>
          <div style="color: #94a3b8; font-size: 0.73rem;">Limits animations for sensory sensitivities</div>
        </div>
        <div style="background: rgba(6,182,212,0.08); border-radius: 8px; padding: 0.5rem 0.75rem;">
          <div style="color: #f5f3ff; font-size: 0.8rem; font-weight: 600;">Face Tracking</div>
          <div style="color: #94a3b8; font-size: 0.73rem;">Camera-based input as an alternative controller</div>
        </div>
        <div style="background: rgba(6,182,212,0.08); border-radius: 8px; padding: 0.5rem 0.75rem;">
          <div style="color: #f5f3ff; font-size: 0.8rem; font-weight: 600;">Audio Toggles</div>
          <div style="color: #94a3b8; font-size: 0.73rem;">Independent SFX and music controls</div>
        </div>
      </div>
    </div>

    <div style="background: rgba(6,182,212,0.05); border-left: 3px solid #06b6d4; border-radius: 0 8px 8px 0; padding: 0.75rem 1rem; margin-top: 0.75rem;">
      <span style="color: #67e8f9; font-size: 0.75rem; font-weight: 700;">Why it matters: </span>
      <span style="color: #c4b5fd; font-size: 0.82rem;">No mainstream game engine ships with IDD-specific modes. Ours was designed with those needs as the baseline — not bolted on. That distinction determines whether a participant can play at all.</span>
    </div>
  </div>

  <!-- Section 3: Social Platform -->
  <div style="margin-bottom: 2rem;">
    <div style="display: flex; align-items: center; gap: 0.75rem; margin-bottom: 1rem;">
      <div style="background: rgba(124,58,237,0.25); border: 1px solid rgba(124,58,237,0.5); border-radius: 8px; padding: 0.3rem 0.7rem; font-size: 0.7rem; color: #a78bfa; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; white-space: nowrap;">Component 03</div>
      <h3 style="color: #f5f3ff; font-size: 1.05rem; font-weight: 700; margin: 0;">Community Hub — Social Platform</h3>
    </div>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1rem;">

      <div style="background: rgba(255,255,255,0.03); border: 1px solid rgba(255,100,100,0.2); border-radius: 12px; padding: 1.1rem;">
        <div style="color: #fca5a5; font-size: 0.7rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.6rem;">Current Site</div>
        <ul style="color: #c4b5fd; font-size: 0.82rem; line-height: 1.75; margin: 0; padding-left: 1.1rem;">
          <li>No online community space of any kind</li>
          <li>Participant relationships exist only during in-person sessions</li>
          <li>No leaderboards, scores, or competitive tracking online</li>
          <li>No multiplayer — competition requires physical co-location</li>
          <li>Community engagement drops to zero between events</li>
        </ul>
      </div>

      <div style="background: rgba(124,58,237,0.08); border: 1px solid rgba(124,58,237,0.3); border-radius: 12px; padding: 1.1rem;">
        <div style="color: #a78bfa; font-size: 0.7rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.6rem;">Our Platform</div>
        <ul style="color: #ddd6fe; font-size: 0.82rem; line-height: 1.75; margin: 0; padding-left: 1.1rem;">
          <li>Microblog feed — participants post, reply, and react</li>
          <li>Per-level leaderboards surfaced directly in the social feed</li>
          <li>Real-time co-op multiplayer rooms via WebSocket</li>
          <li>Persistent profiles that track game progress and community activity</li>
          <li>Year-round engagement independent of scheduled sessions</li>
        </ul>
      </div>

    </div>
    <div style="background: rgba(124,58,237,0.07); border-left: 3px solid #7c3aed; border-radius: 0 8px 8px 0; padding: 0.75rem 1rem; margin-top: 0.75rem;">
      <span style="color: #a78bfa; font-size: 0.75rem; font-weight: 700;">Why it matters: </span>
      <span style="color: #c4b5fd; font-size: 0.82rem;">Social connection is core to UESL's mission — but currently that connection only exists when participants are physically in the same room. The community hub makes it permanent and distance-independent.</span>
    </div>
  </div>

  <!-- Summary -->
  <div style="background: rgba(255,255,255,0.04); border: 1px solid rgba(124,58,237,0.25); border-radius: 12px; padding: 1.25rem;">
    <div style="color: #a78bfa; font-size: 0.72rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.75rem;">Platform Summary</div>
    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; text-align: center;">
      <div>
        <div style="color: #f5f3ff; font-size: 1.4rem; font-weight: 700;">24/7</div>
        <div style="color: #c4b5fd; font-size: 0.75rem; margin-top: 0.2rem;">Program support via chatbot vs. business-hours-only staff</div>
      </div>
      <div>
        <div style="color: #f5f3ff; font-size: 1.4rem; font-weight: 700;">8 modes</div>
        <div style="color: #c4b5fd; font-size: 0.75rem; margin-top: 0.2rem;">IDD-specific accessibility vs. zero accommodations online</div>
      </div>
      <div>
        <div style="color: #f5f3ff; font-size: 1.4rem; font-weight: 700;">365 days</div>
        <div style="color: #c4b5fd; font-size: 0.75rem; margin-top: 0.2rem;">Community engagement vs. in-person sessions only</div>
      </div>
    </div>
  </div>

</div>

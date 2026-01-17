# TermS!gnal 📡  
*A macOS-native BBS terminal with retro soul.*

TermS!gnal is a focused terminal app for macOS, built specifically for connecting to bulletin board systems (BBSes).

Modern terminals are excellent at shells and logs, but they fall apart when it comes to classic BBS behavior: ANSI art flickers, colors break, door games misbehave, and CP437 support is inconsistent at best.

This project exists to fix that.

---

## What Problem Is This Solving?

Most macOS terminals were never designed for:

- ANSI art animations
- Cursor-heavy screen updates
- CP437 character sets
- Real-time door games like *Legend of the Red Dragon*

As a result, classic BBSes often look wrong or feel broken, even though the server side still works perfectly.

TermS!gnal aims to be a **BBS-first terminal**, not a general-purpose shell replacement.

---

## The Goal

Create a **macOS-native terminal app** that:

- Renders ANSI and ASCII art cleanly and accurately  
- Handles classic BBS screen behavior without flicker  
- Plays door games smoothly and correctly  
- Feels modern, but respects the retro experience  

If LORD looks right and plays right, we’re doing it right.

---

## Planned Features (Early Scope)

- Bundled CP437 font with correct glyph mapping  
- Accurate ANSI / VT100-style escape handling  
- Smooth, cell-based screen updates  
- Proper cursor control and positioning  
- Configurable `TERM` values for BBS compatibility  
- Keyboard mapping suitable for door games  
- Telnet and SSH connections (custom ports supported)  

This is intentionally a **small, focused feature set**.

---

## Non-Goals

To keep the project realistic, TermS!gnal is **not** trying to be:

- A full replacement for Terminal.app or iTerm2  
- A web-based terminal  
- A multi-platform solution (macOS first)  
- A perfect emulator for every terminal ever made  

The goal is “excellent for BBSes,” not “everything for everyone.”

---

## Who This Is For

- BBS users on macOS  
- Retro computing enthusiasts  
- Terminal nerds who care about rendering details  
- Developers interested in terminal emulation or text rendering  

---

## About the Project

I’m not a developer. I’m a long-time BBS user with a strong idea of how this *should* feel when it’s right.

This project is a collaboration invitation, not a finished product.  
If you’re interested in helping shape or build it, I’d love to talk.

Issues, suggestions, and discussions are all welcome.

---

## BBSes That Inspired This Project

These systems remind me why terminals still matter:

- **TW Lounge** – telnet://twlounge.ddns.net:7777  
- **Constructive Chaos** – https://conchaos.synchro.net  
- **Last Rangers’** – telnet://lastrangersbbs.com:8888  
- **xibalba.l33t.codes** – ssh://xibalba.l33t.codes:44511  

If you’re on a BBS in 2026, you’re keeping something alive.

Keep typ!ng.

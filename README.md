# Agent Sandbox on EKS: Hardware-Isolated microVM Pods for AI Agents

KubeCon + CloudNativeCon North America 2026, Demo Theater. Wednesday 2026-11-11, 11:25 to 11:45.
Carlos Santana and Todd Neal, AWS.

## Slides

`slides/index.html` is a single self-contained HTML deck: 21 slides, speaker notes, and a
presenter view. Open it in a browser; no server is needed.

| Key | Does |
|---|---|
| `→` `←` Space, PageDown/PageUp | next / previous slide |
| Home / End | first / last slide |
| `p` | open the **presenter view** in a second window: current and next slide, speaker notes, elapsed timer and clock. The two windows follow each other. |
| `n` | show the notes under the current slide |
| `f` | full screen |
| `?` | key help |
| presenter: `t`, `+`, `-` | reset the timer, resize the notes |

Put the deck window on the projector, press `p`, drag the presenter window to the laptop
screen. The presenter bar names the speaker for the current slide.

**Co-presenter.** The deck is given twice with different co-presenters. Open
`slides/index.html` for Todd Neal (the default) or `slides/index.html?with=aaresh` for
Aaresh Sharma: the title and closing slides, the presenter bar and every note that names the
co-presenter switch together, and the presenter window inherits the choice.
`slides/index.html?with=solo` is Carlos alone: no co-presenter block and no hand-offs in the
notes. The title slide names only the conference; add `&venue=Theater%20B` to any variant to
put a venue after it.

Slides 1 to 10 are Carlos (why, the Kubernetes-native shape, demo); 11 to 18 are the
co-presenter, or Carlos when solo (RuntimeClass, containerd, the confidential use case, Cedar, attestation, the
reference implementation); 19 and 20 are the blueprints call to action and thanks; 21 is the
EKS workshops and Agents After Hours promo that stays up after the talk.

## Files

- `slides/index.html`: the deck.
- `slides/carlos-santana.jpg`, `slides/todd-neal.jpg`, `slides/aaresh-sharma.jpg`: speaker photos.
- `slides/sandboxing-how-it-works.png`: the slide 11 architecture diagram.
- `slides/blueprints-qr.svg`, `slides/workshops-qr.svg`, `slides/after-hours-qr.svg`: QR codes for
  the blueprints repository, <https://awsworkshop.io/eks> and <https://s12d.com/agents-after-hours>.

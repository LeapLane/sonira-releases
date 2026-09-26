# Sonira

**Voice-to-text for the Mac that turns speech into clean, ready-to-send writing, in every app.**
Hold one key, say what you mean, and the finished sentence lands where the cursor is. The
filler words, the false starts and the "no wait, scratch that" are gone before you see the text.

Sonira speaks English, European Portuguese and Brazilian Portuguese as three different
languages, not one bucket. The cleanup pass is forbidden from converting one variant into
another, or from formalising how you actually talk.

**[sonira.app](https://sonira.app)** has the full story.

This repository hosts the public download and the auto-update manifests. The source code lives
in the private `LeapLane/sonira` repo, so only signed, notarized release artifacts are published
here.

## Download

**[Download Sonira for macOS](https://github.com/LeapLane/sonira-releases/releases/download/stable/Sonira.dmg)**
(universal, Intel + Apple Silicon). Open the `.dmg`, drag **Sonira** to **Applications**, launch it.

Free while in beta. Windows is next.

On first launch Sonira walks you through the two macOS permissions it needs: Accessibility and
Input Monitoring, so the hold-to-talk key works, and microphone access. Nothing is dictated
until you hold the key.

## Guides

Written for someone deciding what to dictate with, not for a search engine. Each one is useful
with whatever tool you already use, including the one Apple already gave you.

- [How to dictate on a Mac](https://sonira.app/how-to-dictate-on-mac). The Dictation already
  built into macOS, set up step by step, and where a dedicated app starts to earn its place.
- [Mac dictation apps compared](https://sonira.app/mac-dictation-apps). Eleven options,
  including the ones we lose to, and what each is actually for.
- [Wispr Flow alternatives, sorted by why you are leaving](https://sonira.app/wispr-flow-alternatives).
  Six reasons people leave, and the tool that answers each one.
- [Sonira and Wispr Flow, compared honestly](https://sonira.app/wispr-flow-alternative).
  Where we are better, and where we are not there yet.
- [What a free dictation tier is really worth](https://sonira.app/free-dictation-apps). Every
  free plan converted into the same unit: minutes of talking.
- [Dictating in two languages](https://sonira.app/dictating-in-two-languages). What happens to
  a sentence that carries English jargon inside another language, and which half breaks.
- [Dictation with an accent](https://sonira.app/dictation-with-an-accent). What speech to text
  really gets wrong when English is not your first language. It is rarely the accent.
- [Portuguese voice dictation on a Mac](https://sonira.app/portuguese-voice-dictation).
- [European vs Brazilian Portuguese dictation](https://sonira.app/european-vs-brazilian-portuguese-dictation).
- [Which Mac dictation apps actually support European Portuguese](https://sonira.app/portuguese-dictation-apps).

### Em português de Portugal

- [Ditado por voz em português](https://sonira.app/pt-PT/ditado-por-voz). O guia completo, para Mac.
- [Português de Portugal vs do Brasil](https://sonira.app/pt-PT/portugues-de-portugal-vs-brasil).
  O que muda no ditado, e porque é que quase todas as ferramentas escrevem brasileiro.
- [Ditar com inglês pelo meio](https://sonira.app/pt-PT/ditar-em-portugues-e-ingles). O que
  acontece à frase de trabalho que leva palavras inglesas.
- [Que apps percebem mesmo português de Portugal](https://sonira.app/pt-PT/apps-de-ditado-em-portugues).
  Fomos aos sites de quinze fabricantes contar.

### Em português do Brasil

- [Ditado por voz em português](https://sonira.app/pt-BR/ditado-por-voz). O guia completo, para Mac.
- [Português do Brasil vs de Portugal](https://sonira.app/pt-BR/portugues-de-portugal-vs-brasil).
  O que muda no ditado, e por que quase toda ferramenta trata os dois como um só.
- [Ditar com inglês no meio](https://sonira.app/pt-BR/ditar-em-portugues-e-ingles). O que
  acontece com a frase que mistura os dois.
- [Quais apps entendem português do Brasil](https://sonira.app/pt-BR/apps-de-ditado-em-portugues).
  Abrimos o site de quinze fabricantes e contamos.

## Channels

Auto-updates are delivered per channel via a rolling release whose tag is the channel name:

| Channel  | Audience        | Manifest |
|----------|-----------------|----------|
| `stable` | everyone        | `releases/download/stable/latest.json` |
| `dev`    | internal        | `releases/download/dev/latest.json` |

Assets on each channel release are overwritten on every publish, so the URLs above are permanent.

## Issues

Bug reports and feature requests are welcome in this repository's issue tracker. The private
source repo is where they get fixed.

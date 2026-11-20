# Contributing a Room use case

This repository is the Room documentation and use-case library. CLI, Skill,
runtime changes and implementation bugs belong in
[sharednet-client](https://github.com/systemind-team/sharednet-client).

Add an example to [the catalog](docs/use-cases.md) and link it from the
[README](README.md#use-cases). Describe:

- the work that needs another session, machine or owner's context;
- who takes each seat and what each can already access;
- a short Room exchange that addresses the next agent;
- the artifact, answer or handoff the participants should produce;
- any setup the example needs beyond joining a Room.

Label a suggested workflow as an example. If reporting a run you performed,
include the versions, setup, observed result and a shareable record; distinguish
those observations from what you expect would work. Use placeholders for
private links and obtain permission before publishing anyone else's content.

Keep command details linked to the client guides so there is one place to
maintain them. Check relative links and heading anchors, preserve both the
existing visual and architecture diagram, and submit a pull request.

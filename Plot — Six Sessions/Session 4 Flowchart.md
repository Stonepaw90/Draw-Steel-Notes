---
notion-id: d8f2a9b3-7c12-48e1-a2d5-f6e8c9b0a1d2
---
[[Plot — Six Sessions]] · [[Session 4 — Demigods in the Mines]] · [[Vasloria - A living encylopedia]]

## Session 4 Flowchart: Demigods in the Mines

```mermaid
flowchart TD
    Start([Start Session 4]) --> Dream{Blue Eyes Dream}
    Dream ---|Warns of demigods| MineCollapse
    
    subgraph Northern_Mine [Northern Mine/Laboratory]
        direction TB
        MineCollapse((Mine Collapse)) --> Rescue[Rescue Dwarves & Ghouls]
        Rescue --> InjuredDwarf(Explain Experiment)
        InjuredDwarf --> RuinedLab{Ruined Laboratory}
    end
    
    subgraph Demigods_Division [Demigods Disagreement]
        direction TB
        RuinedLab ---|Green light| AweSupportsStone[Awe Supports Stone]
        RuinedLab ---|Maiden action| MaidenRescues[Maiden Rescues Creatures]
        AweSupportsStone --- Disagreement{Creation vs Improvement}
        MaidenRescues --- Disagreement
    end
    
    subgraph Demigods_Positions [Demigods Positions]
        direction TB
        Disagreement --- Fealti[Fealti: Wants Family & Games]
        Disagreement --- Awe[Awe: Nature Love]
        Fealti --- MaidenWarning[Maiden: Elementalist's Death]
    end
    
    subgraph Transformations [Transformations & Key]
        direction TB
        MaidenWarning --- GhoulTransform[Maiden Transforms Ghoul]
        GhoulTransform --- ConnectAurumvas[Connect with Aurumvas]
        ConnectAurumvas --- ListeningKey{Listening Key}
    end
    
    subgraph Character_Reactions [Character Reactions]
        direction TB
        Start --- Drokki[Drokki: Fears Great Age]
        Start --- Dealoken[Dealoken: Magically Present]
        Start --- Theodora[Theodora: Divine Power]
        Start --- Gruin[Gruin: Awe as Old Friend]
        Start --- Xarnath[X'arnath: Recognizes Aurumvas]
        Start --- Isolde[Isolde: Epic Inspiration]
        Start --- Oslin[Oslin: Soul Stirs]
    end
    
    ListeningKey --> End([End Session 4])
    
    %% Hover text for nodes is embedded in the displayLabel
    style Start fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    style Dream fill:#fff9c4,stroke:#fbc02d,stroke-width:2px
    style MineCollapse fill:#ffebee,stroke:#c62828,stroke-width:2px
    style Rescue fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
    style InjuredDwarf fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px
    style RuinedLab fill:#eceff1,stroke:#546e7a,stroke-width:2px
    style AweSupportsStone fill:#e0f7fa,stroke:#00897b,stroke-width:2px
    style MaidenRescues fill:#fff3e0,stroke:#ef6c00,stroke-width:2px
    style Disagreement fill:#fce4ec,stroke:#ad1457,stroke-width:2px
    style Fealti fill:#f8bbd0,stroke:#880e4f,stroke-width:2px
    style Awe fill:#d1c4e9,stroke:#4a148c,stroke-width:2px
    style MaidenWarning fill:#ffccbc,stroke:#bf360c,stroke-width:2px
    style GhoulTransform fill:#e1bee7,stroke:#6a1b9a,stroke-width:2px
    style ConnectAurumvas fill:#c8e6c9,stroke:#1b5e20,stroke-width:2px
    style ListeningKey fill:#b2dfdb,stroke:#004d40,stroke-width:2px
    style End fill:#f5f5f5,stroke:#424242,stroke-width:2px
```

## Node Details (Hover Text)

| Node | Brief Title | Full Description |
|------|-------------|------------------|
| Start | Session 4 Begins | A dream featuring blue eyes warns of the demigods' activities before a nighttime collapse in the northern mine. |
| Dream | Blue Eyes Dream | The party experiences a prophetic dream with blue eyes, warning them about Fealti and Awe's experiments beneath Shelter. |
| MineCollapse | Northern Mine Collapse | A nighttime collapse brings dust, cries for help, trapped dwarves, and ghouls that need urgent rescue. |
| Rescue | Rescue Operation | The party works to free the injured dwarves and displaced ghouls from the collapsed mine tunnels. |
| InjuredDwarf | Experiment Explanation | An injured dwarf reveals an experiment went wrong; prejudice may complicate accepting healing from a stone dwarf. |
| RuinedLab | Laboratory Discovery | A green light and ruined laboratory reveal where Awe supports stone while the Maiden rescues creatures. |
| AweSupportsStone | Awe's Position | Awe wants to improve the beings' lives and provide a love of nature rather than obsession with Fealti. |
| MaidenRescues | Maiden's Action | The Maiden focuses on rescuing creatures in the laboratory, disagreeing with Awe about creation vs improvement. |
| Disagreement | Demigods Debate | The core conflict: should they create anew or improve existing attempts? They speak of needing their brother. |
| Fealti | Fealti's Proposal | Claims she wants a family and provides housing, feasts, and public games for the party. |
| Awe | Awe's Vision | Advocates for nature-based love and better lives for all beings rather than divine obsession. |
| MaidenWarning | Maiden's Prophecy | Refers to the Elementalist's death and predicts heroes will never heal the dwarves' divide. |
| GhoulTransform | Animated Ghoul | The Maiden transforms a ghoul into an animated ghoul in front of the party as demonstration. |
| ConnectAurumvas | Contact Aurumvas | The Maiden asks heroes to connect her with Aurumvas; completion of follow-ups not separately recorded. |
| ListeningKey | Living Key | The party receives a key that listens to them and can be flipped to speak with the Maiden's voice. |

## Notable Events

- **Prepared rescue** - Collapse brings dust, cries for help, dwarves, and ghouls needing rescue
- **Disagreement** - Demigods debate whether to create anew or improve existing attempts
- **Transformations** - Ghoul transformed into animated ghoul; key with speaking ability given to party
- **Character reactions** - Each party member had distinct reactions to the demigods' presence and powers

[[Session 3 — Ghouls and Demons]] · [[Session 5 — The House of Clan Lodgy]]

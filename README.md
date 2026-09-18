<div align="center">

# SATELLITE VESSEL INTELLIGENCE

## CASE 01 — UNKNOWN CONTACT → CRUDE OIL TANKER


### Intelligence Question

What vessel is represented by the unidentified EO contact, and does the available evidence support both its classification and individual identity?

</div>

---

### 01 · Detection

A single maritime contact is detected in commercial EO imagery.

The object is sufficiently resolved to examine its hull geometry, deck arrangement and major structural features. The image provides enough visual information for classification, while some fine details remain subject to image resolution and viewing conditions.

<div align="center">

![Crude Oil Tanker — Satellite Vessel Intelligence](assets/case-studies/Tanker.png)

</div>

> **Imagery note:** The EO scene shown here is illustrative/synthetic imagery created for portfolio demonstration. It is not an operational satellite acquisition or proprietary client imagery.
>
> **Analytical note:** The case demonstrates the vessel-identification methodology and evidence-reconciliation workflow. Synthetic imagery is used only to illustrate the visual-analysis component.

---

### 02 · Object Determination

The contact is assessed as a **vessel** rather than a fixed structure, platform or other maritime object.

The determination is supported by:

- Defined bow and stern
- Continuous hull geometry
- Symmetrical vessel form
- Deck arrangement consistent with a ship
- Position and orientation within navigable water

**Object determination confidence: HIGH**

---

### 03 · Observed characteristics

| Feature | Observation |
|---|---|
| Hull | Long, broad commercial hull |
| Cargo deck | Continuous central deck area |
| Accommodation | Positioned toward the aft |
| Deck infrastructure | Visible longitudinal piping |
| Cargo arrangement | No visible container stacks |
| Cargo handling | Central manifold / deck crane features |
| Hatch arrangement | No prominent bulk-carrier hatch pattern |

---

### 04 · Competing Hypotheses

| Hypothesis | Supporting Evidence | Contradicting Evidence |
|---|---|---|
| Crude oil tanker | Broad hull, continuous cargo deck, piping, tanker geometry | Cargo carried cannot be confirmed visually |
| Product tanker | Similar tanker configuration | Overall dimensions / proportions less consistent |
| Bulk carrier | Commercial vessel proportions | Lack of prominent cargo hatches |
| Container vessel | Commercial hull | No container-stack arrangement |

---

### 05 · Classification 

The contact is classified as an **oil tanker** with HIGH confidence.

The classification is supported by the convergence of:

- Hull proportions
- Continuous cargo deck
- Visible deck piping
- Aft accommodation
- Manifold configuration
- Absence of container-stack or bulk-carrier hatch characteristics

<div align="center">
        
**Classification Confidence: HIGH**

</div>

**Important distinction:** classification identifies the vessel type; it does not establish the individual vessel identity.

---

### 06 · Candidate Generation

Once the contact was classified as an oil tanker, AIS data within the relevant acquisition window was used to identify candidate vessels occupying the corresponding geographic area.

Candidate filtering considered:

1. Spatial proximity to the EO contact
2. Temporal proximity to image acquisition
3. Vessel type
4. Reported length / beam
5. Vessel orientation
6. Availability of independent vessel particulars


The strongest AIS candidate was tested against the EO contact using spatial, temporal and physical characteristics.

| Candidate | AIS Type | LOA/Beam | Spatial Match | Temporal Match | Physical Match |
|---|---|---|---|---| ---|
| AMANTEA | Tanker | 329.98 m/60 m | ✓ | ✓ | ✓ |
| LNG VENUS | Tanker | 288 m/48.94 m | x | ✓ | x |


**Correlation assessment:** The candidate's reported dimensions, vessel type, position and timing are consistent with the physical characteristics observed in the EO image.

The AIS position and timestamp are consistent with the satellite acquisition, while the reported dimensions, vessel type and orientation are broadly consistent with the observed contact.

---

### 07 · EO → AIS Correlation

The strongest AIS candidate was tested against the EO contact using spatial, temporal and physical characteristics.

| Evidence Layer | EO Observation | AIS / Vessel Record | Correlation |
|---|---|---|---|
| Vessel type | Tanker-like configuration | Tanker | Consistent |
| Length | ~330 m estimated | 329.98 m | Consistent |
| Beam | ~60 m estimated | 60 m | Consistent |
| Orientation | [Observed heading/orientation] | Course 237° | Consistent / [explain] |
| Position | [EO acquisition area] | [AIS position] | Spatially consistent |
| Acquisition time | [EO timestamp] | 15 Sep 2026, 07:35 UTC | Temporally consistent |
| Hull configuration | Tanker architecture | Crude oil tanker particulars | Consistent |

**Correlation assessment:** The candidate's reported dimensions, vessel type, position and timing are consistent with the physical characteristics observed in the EO image.

---

### 08 · Vessel Particulars Cross-Check

Independent vessel records identify **AMANTEA (IMO 9892810)** as a crude oil tanker with documented dimensions of approximately **330 m × 60 m**.

| Particular | EO Assessment | Independent Record | Result |
|---|---:|---:|---|
| Vessel type | Oil tanker | Crude oil tanker | Consistent |
| Length | ~330 m | 330 m | Consistent |
| Beam | ~60 m | 60 m | Consistent |
| IMO | — | 9892810 | Identity anchor |

 > **The independent vessel record strengthens the classification but does not replace the EO/AIS correlation required for individual identity resolution.**

---

### 09 · Identity Assessment

**Object Confidence       HIGH**
**Classification Confidence HIGH**
**Identity Confidence      HIGH**

The EO characteristics support an oil-tanker classification, while the correlated AIS transmission and independent vessel particulars provide additional evidence for resolving the contact to **[AMANTEA]**.

> **Analyst Note:** AIS correlation strengthens identification but is not treated as conclusive where timing, position, dimensions or physical characteristics present material inconsistencies.

---

### 10 · Final Assessment

**The EO contact is assessed as AMANTEA (IMO 9892810), a crude oil tanker.**

The assessment is supported by the convergence of:

**EO vessel architecture**
+
**estimated dimensions**
+
**temporally and spatially correlated AIS**
+
**independent vessel particulars**

The evidence supports **HIGH confidence in both classification and individual-vessel identity**.

> **Analyst Note:** AIS correlation is treated as supporting evidence rather than standalone proof of identity. Material disagreement in timing, position, dimensions or physical configuration would reduce identity confidence.

---


<div align="center">

## CASE 02 — UNKNOWN NAVAL CONTACT → SURFACE COMBATANT CLASSIFICATION

### Intelligence Question

What vessel classification can be supported from degraded EO imagery when no directly correlated public AIS identity is available?

---

### 01 Detection

An unidentified maritime contact was detected alongside a fictionalized coastal naval facility in commercial EO imagery.

The contact was sufficiently resolved to assess its overall hull geometry, major superstructure, deck configuration and selected dimensions. Atmospheric haze limits the visibility of finer structural details.

![Unknown Naval Contact — Satellite Vessel Intelligence](assets/case-studies/Naval-vessel.png)

</div>

> **Imagery note:** The EO scene shown here is illustrative/synthetic imagery created for portfolio demonstration. It is not an operational satellite acquisition or proprietary client imagery.
>
> **Analytical note:** The case demonstrates the vessel-identification methodology and evidence-reconciliation workflow. Synthetic imagery is used only to illustrate the visual-analysis component.

---

### 02 Object Determination

The contact is assessed as a vessel rather than a fixed maritime structure, platform or other object.

#### Observed indicators

- Defined hull with clear bow and stern geometry
- Vessel-like longitudinal proportions
- Central superstructure rising from the hull
- Aft deck area consistent with a vessel flight deck
- Position alongside a pier within the fictionalized naval facility

**Object Confidence: HIGH**

---

### 03 Observed Characteristics

| Feature | Observation | Visibility |
|---|---|---|
| Hull | Long, relatively narrow hull | Clear |
| Superstructure | Large central superstructure | Clear |
| Forward structure | Forward gun-like structure visible | Moderate |
| Sensors | Radar/sensor structures visible above superstructure | Moderate |
| Aft deck | Large clear aft deck consistent with flight-deck configuration | Clear |
| Cargo configuration | No visible commercial cargo arrangement | Clear |
| Overall dimensions | Large surface-vessel proportions | Moderate |
| Fine structural details | Partially obscured by atmospheric degradation | Limited |

---

## 04 Competing Hypotheses

### Hypothesis A — Large Naval Surface Combatant

Supported by:

- Long, narrow hull
- Large centralized superstructure
- Radar/sensor structures
- Forward weapon configuration
- Aft flight deck
- Absence of commercial cargo infrastructure


### Hypothesis B — Frigate

Some characteristics are compatible with a frigate-type configuration, particularly the overall hull and superstructure arrangement.

However, the apparent scale and configuration provide limited support for a more specific frigate assessment.

### Hypothesis C — Patrol / Support Vessel

The contact is clearly larger and more structurally complex than a typical patrol configuration, making this hypothesis less consistent with the observed characteristics.

---

### Classification

The physical configuration is most consistent with a **large naval surface combatant**.

...

**Classification Confidence: MEDIUM–HIGH**

---

### Assessment

The observed characteristics most strongly support classification as a large naval surface combatant.

The contact is assessed as a **large naval surface combatant**, with **MEDIUM–HIGH classification confidence**.

The assessment is based primarily on:

- Overall hull geometry
- Centralized superstructure
- Radar/sensor configuration
- Forward gun-like structure
- Aft flight-deck arrangement
- Absence of commercial cargo characteristics
- Estimated vessel dimensions

The available imagery does not provide sufficient detail to support attribution to a specific individual vessel or definitive class designation.

---

### 06 Temporal & Geospatial Context

| Evidence Layer | Observation | Analytical Relevance |
|---|---|---|
| Image acquisition | [DATE / TIME] | Establishes observation timeframe |
| Location | Fictionalized coastal naval facility | Provides contextual setting |
| Berth relationship | Contact positioned alongside naval infrastructure | Consistent with naval-vessel interpretation |
| Orientation | [Observed orientation] | Supports geometric assessment |
| Dimensions | [Estimated dimensions] | Supports vessel-scale assessment |
| Image conditions | Haze / atmospheric degradation | Limits fine-detail interpretation |

> **The contextual evidence supports the interpretation of the contact as a naval surface vessel but does not independently establish individual vessel identity.**

---

### AIS / Identity Availability

No directly correlated public AIS identity is available for this fictionalized case.

AIS availability alone is therefore not treated as evidence for or against the vessel's identity.

---

### Confidence Assessment

| Assessment Layer | Confidence |
|---|---|
| Object determination | HIGH |
| Vessel classification | MEDIUM–HIGH |
| Individual vessel identity | UNRESOLVED |

---

## 07 Analytical Limitations

The available evidence supports classification of the contact as a large naval surface combatant.

However, the available imagery and contextual information do not establish:

- A specific vessel identity
- IMO or MMSI
- Vessel name
- Flag
- Definitive class designation
- A unique hull number

These elements remain unresolved.

---

## 08 Final Assessment

The contact is assessed as a **large naval surface combatant**, with **MEDIUM–HIGH classification confidence**.

The assessment is supported by the vessel's hull geometry, centralized superstructure, sensor configuration, forward weapon structure and aft flight-deck arrangement. Atmospheric degradation limits the visibility of finer structural characteristics but does not prevent assessment of the overall vessel configuration.

**Individual vessel identity remains UNRESOLVED.**

This case therefore demonstrates classification under imperfect EO conditions rather than individual-vessel identity resolution.


> **Analyst Note:** The absence of a directly correlated public AIS identity is not treated as evidence of military status or identity. The assessment is based on observable vessel characteristics and contextual information available within the case.

---

<div align="center">

# SATELLITE VESSEL INTELLIGENCE

**Detect · Observe · Measure · Classify · Assess**

Transforming overhead imagery into structured vessel intelligence through visual analysis, spatial measurement and evidence-based classification.

</div>

---

## Intelligence Question

### What can observable vessel characteristics reveal from overhead imagery?

Overhead imagery can provide evidence of a vessel's presence, geometry, dimensions, deck configuration and structural characteristics.

The objective is not simply to identify an object as a vessel.

The objective is to determine **what can be reliably observed, what those observations may indicate, and what classification can be supported by the available evidence.**

---

## 01 — Observation

The analysis begins with the imagery itself.

The first question is:

> **What is directly visible?**

Observable characteristics may include:

- Overall vessel geometry
- Hull shape and proportions
- Bow and stern configuration
- Deck layout
- Cargo arrangement
- Superstructure and bridge position
- Cranes, piping or other visible infrastructure
- Relationship to surrounding maritime infrastructure

The detected object is first assessed as:

**Vessel · Barge · Platform · Buoy · Other · Unresolved**

> **Analytical principle:** A classification is not assigned before the observable object has first been identified.

---

## 02 — Identification

Once an object is assessed as a vessel, the analysis considers its observable physical and structural characteristics.

The objective is to establish the broad vessel category before moving toward a more specific classification.

### Broad Class

Examples may include:

- Cargo
- Tanker
- Passenger
- Pleasure
- Fishing
- Offshore
- Other

### Subclass

Where sufficient evidence is available, the assessment may be refined to a more specific vessel type.

Examples may include:

- General Cargo
- Bulk Carrier
- Container Vessel
- Crude Oil Tanker
- Product Tanker
- LPG / LNG Carrier
- Ferry
- Yacht

> **Classification is based on converging characteristics rather than a single visual feature.**

---

## 03 — Measurement

Vessel geometry provides additional evidence for classification.

The primary measurements assessed are:

| Measurement | Analytical Use |
|---|---|
| **Length Overall (LOA)** | Approximate vessel length from the forward-most to aft-most visible extent |
| **Beam** | Approximate maximum vessel breadth |
| **L/B Ratio** | Additional indication of overall vessel proportions |

Where imagery scale or Ground Sampling Distance is known:

```text
Physical Distance = Pixel Distance × Ground Sampling Distance

```

Measurement confidence may be affected by image resolution, vessel orientation, georeferencing accuracy, shadow, wake and partial occlusion.

> Dimensions support classification but do not independently determine vessel type.

---

## 04 — Classification

Classification combines vessel geometry with observable structural evidence.

The assessment may consider:

- Hull proportions
- Deck configuration
- Cargo structures
- Superstructure location
- Bridge positioning
- Cargo-handling infrastructure
- Deck cranes
- Visible piping
- Container geometry
- Specialized containment structures

These observations may then be assessed against vessel categories and subclasses.

```text
OBSERVABLE STRUCTURE
        +
VESSEL GEOMETRY
        +
DIMENSION ESTIMATES
        ↓
CLASSIFICATION HYPOTHESIS
```

The resulting assessment is expressed as an analytical conclusion rather than an assumed fact.

For example:

>**Observed deck configuration and vessel proportions are consistent with a tanker arrangement. The available imagery supports a crude oil tanker hypothesis.**

---

## 05 — Status Assessment

The vessel's apparent operational state is assessed from the available imagery.

**Status	Assessment**
- Sailing / Underway	Evidence suggests active movement or an underway state, identified by presence of a wake.
- Stationary	Vessel appears stationary at the time of observation
- Unknown	Available imagery does not support a reliable status assessment

A single image represents a specific moment in time.

Observed position should not automatically be interpreted as a complete behavioural pattern.

Where additional information is available, imagery observations may be correlated with AIS or other maritime data.

---

## 06 — Confidence

Confidence reflects the strength and quality of the evidence supporting the
assessment.

| Level | Intelligence Assessment |
|---|---|
| **HIGH** | Multiple independent visual indicators converge, image quality is sufficient, and limited ambiguity remains in the assessment. |
| **MEDIUM** | The classification is plausible and supported by some evidence, but one or more relevant characteristics remain obscured, ambiguous or unresolved. |
| **LOW** | Available evidence is limited, conflicting or insufficient to support a reliable classification. |

### Confidence Factors

>**Confidence** is determined through an assessment of factors including:

- Image resolution and overall quality
- Sensor or imagery type
- Vessel visibility
- Vessel orientation
- Observable structural detail
- Degree of occlusion
- Shadow and wake interference
- Measurement reliability
- Availability of corroborating information
- Consistency between independent indicators

>**Confidence reflects the strength of the available evidence — not the certainty of the analyst.**

---

## 07 — Intelligence Assessment

Each analysed object is recorded as a structured assessment:

```text
OBJECT TYPE
        ↓
VESSEL CLASS
        ↓
VESSEL SUBCLASS
        ↓
LENGTH + BEAM
        ↓
STATUS
        ↓
EVIDENCE
        ↓
CLASSIFICATION
        ↓
CONFIDENCE
```

The final assessment distinguishes between:

**Observed characteristics**
What is directly visible in the imagery.

**Inference**
What those characteristics may indicate.

**Classification**
The vessel type most consistent with the available evidence.

**Confidence**
The strength of the evidence supporting that assessment.

>**NOTE: A hypothesis is never presented as an observed fact.**

---


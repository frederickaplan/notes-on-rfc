---
title: 'RFC on Data Graph'
subtitle: 'No number'
author:
- Fréderic Kaplan

# Don't change the following lines
header-includes:
- \usepackage{fancyhdr}
- \pagestyle{fancy}
- \fancyfoot[L]{-release-version-}
output: pdf_document
---

# Note on Data Graph

## Motivation

As simple as possible. As complex as necessary. 

## Approach

Part taken from RFC5 : 

The **4D Map** has a series of standard Layers that are fully defined in a dedicated RFC  (**Not currently planned in RFC2**)


1. The **Municipalities** segmentation that defines the granularity of the **Local Time Machines**
2. The **Points of View** Layer that corresponds to the perspectives of photographs or paintings. 
3. The **Parcel Layer** :  2D polygon with temporal extension typically defined by an administrative source (e.g. Parcels of the Napoleonic Cadastter of 1808). Each parcel has a unique ID in the Time Machine system.
4. The **Place names** Layer
5. The **Spherical Image** Layer 
6. The **Cloud Point** Layer
7. The **4D Vectorial** Layer
8. The **Homologous Point Network**, connecting images with one another through homogous point 



### One Graph End-to-End from Sources to Concepts

Includes annotation of document

Any conceputal change may have an effect on how we read/interpret a document 

### Bright Graph, Dark Graph

### Incrementality 

TMO will help setting up ingestion pipelines in a sequential order, structuring progressively the information graph offering ways to more easily ingest certain form of structured sources. Local Time Machine Academy events will be regularly organised to help local communities to use these standard tools as they are being developed. These events will also serve to exchange best practices and consolidate prototypes for future ingestion pipelines.

Consolidated Time Machine Pipelines enable to build the Data Graph in incremental way, starting from the core information structure and progressively attaching the small branches and the leaves. Consolidated Time Machine Pipelines are also the main service that helps small Local Time Machines that are not linked with academic research. This is the cast for hundreds of (smaller) cities across Europe.

| 2020  – 2024 | Information  Skeleton: Maps, Cadastres, Address Books, Simple 3D, Statistics, Genealogy,  Census Data |
| ------------ | ------------------------------------------------------------ |
| 2022  – 2026 | Visuals  and Environment Photos and 3D models, Engraving, Paintings, Library of  Objects, Sculptures and Buildings, Photogrammetric models |
| 2024  – 2028 | Events  Newspapers, Radio, news TV programs, Chronicles      |
| 2026  - 2030 | 2030  … all the rest (including private documentation)       |

Indicative schedule of overlapping period of the ingestion of structured documents



### No objects, just histories

### The Open Refine Philosophy

### Learning from Excel

Excell is still one of the most used tool. Why. 

### Global optimization of the Graph

### Famous Subgraphs

- Segments on the Hyperimage
- 
- Hyperdirectory
- Hypercadaster



## Structure of the Graph

### IIIF Document

### Image

All following elements include an **History**

### Point

- Relative to an image
- Can be linked to other points representing the same thing (homologous points) in another image or in the **4D Map** 

### Polygon

- Made of points
- Can be linked to other polygon representing the same thing (homologous polygon) in another image or in the **4D Map**

### Segment (2D)

Segments can be defined on images (Photograph, Maps) and on the **4D Map** (Parcel, house)

- Defined by **Polygon**
- Include a limited set of universal  field 
  - Automatic Transcriptions
  - Manual transcriptions
  - Most-likely transcription
  - Wikidata
  - Describe a subject/object or a relation
  - Formula, how the segment is resulting from symbolic operation on other segment (cell)

- Homolgous Segment can be created by different operations

To be defined : 3D Segment, 4D segment, Node (People, Place, Things), etc

## Homologous Pairs

Example when two points are moved on the **4D Map** they can be merged in the scanned image of the map. 



## Graph Editor

### Segment Editor

### Geographical Editor

### Node Editor



## Question and Answers 



## Linked RFCs


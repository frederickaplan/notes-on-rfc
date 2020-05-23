---
title: 'RFC on 4D Map'
subtitle: 'No number'
author:
- Nils Hamel
- Fréderic Kaplan

# Don't change the following lines
header-includes:
- \usepackage{fancyhdr}
- \pagestyle{fancy}
- \fancyfoot[L]{-release-version-}
output: pdf_document

---

# Note on RFC on Photogrammetric Pipeline

## Motivation



## Approach



## Concepts

#### Global Image Repository

A single repository for Time Machine

#### Global Adjancy Matrix

Indicatng which imiages of the Global Image Repository are sharing parts and hence have homolous points

#### Relative Spatiotemporal positionning between two images

Rotation and translation in time and space between two images of the Global Image Repository. 

#### Homologous Point Network

Global network of all homologous pairs. 



## Workflow

- Calculation of odometry of individual models
- Densification of individuals models.
- Compution of Global 3D odometry using adjancy matrices 
- The global odometry model is georeferenced to be displayed in a standard coordinates system
- Optimal Densification of the global model realigning individual densified model 
- Ingestion in 4D Server

### Computing and Storage

- 70 Mo points = 1 Go (binary)

- Densification roughly multiplies by 10 the number of points and size of the file

- Mesh roughly doubles the size of the dense file

## Question and Answers 



## Linked RFCs


Attempt to design a modular medieval game asset pack to be used in Web VR and other environments.

## Design Principles

* Highly modular
* Atomic: Different level of building blocks
* Reasonable & easy to assemble origins
* Performance: Different level of details
* Easy to add to and extend from
	* Perceiving original vex

### Grid
1 unit = 1 meter

0.1 as the unit for outer boundary (and easy to move around in 1, 3, 7 modes in Blender)

### Materials

Name materials by what they are, not where they are used.

Providing both BI rendering and Cycle rendering materials so it can be super easy to use or to be baked.

One meta object that contains all materials.

## Objects

### Exterior

Adopting atomic design principles for exterior building blocks, so the same assets can be used to create infinite amount of different buildings.

#### 1. Atoms

#### 2. Molecules

#### 3. Organisms

### Interior
Objects + Arbitrary Groups.

#### 1. Furnitures
Origin set to the far left bottom corner of the object.

#### 2. Wall Decors
Origin set to the far center.

#### 3. Large Objects
Origin set to the bottom center.

#### 4. Smaller Objects (<0.5x0.5x0.5)
Origin set to the bottom center.

#### 5. Object Groups

## Usage
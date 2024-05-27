---
title: The SI System
parent: Engineering Maths
nav_order: 2
---

# The SI System

## Overview

Within the UK, the SI system forms the default unit system for science and engineering. Unless you are dealing with historic artefacts, _do not use_ the UK [historic units]({{ site.baseurl }}/reference/obsolete/imperial.html). Even if they are still common in some other areas of the world. For all drawings, calculations, and other technical writing the SI system is the _only_ unit system you should use by choice.

For practical guidance on using the SI units in calculations, drawing, graphs and other documentation see the [How To on Quantities and Units]({{ site.baseurl }}/howto/write/units.html). The details of specific SI base and derived units are in the [reference section]({{ site.baseurl }}reference/si/units.html), along with other [defining features ]({{ site.baseurl }}/reference/si/index.html).

## Core Concepts of the SI Unit System

The [SI system]({{ site.baseurl }}/reference/si/index.html) defines a coherent set of units, based on [seven fundamental constants]({{ site.baseurl }}/reference/si/constants.html). Replacing older unit systems (SI Brochure, (2019))

> The International System of Units, the SI, has been used around the world as the preferred system of units, the basic language for science, technology, industry and trade since it was established in 1960 by a resolution at the 11th meeting of the Conférence Générale des Poids et Mesures, the CGPM (known in English as the General Conference on Weights and Measures).

The SI bases its structure on the abstract notion of a _value_ for any measured, defined or described _quantity_. Abstract values of a quantity become concrete from the product of a _numerical value_ and a _unit_. Quantity values tie to one or more of seven fundamental [constants]({{ site.baseurl }}/reference/si/constants.html)), with constants also expressed in SI units. Thus any SI unit is either itself a fundamental constant, or defined through the products or quotients of defining constants.

Conversely, a number multiplying the unit is the _numerical value_ of the quantity expressed in that unit. The seven fundamental units tie to a [defining constant]({{ site.baseurl }}/reference/si/units.html#base-quantities-and-units) for that unit. By fixing the exact numerical value of the defining constant, the fundamental unit then also becomes defined (as discussed below).

![Interdependence of the Seven SI base Units and Defining Constants as their 2019 Redefinition (Pisanty, 2018)]({{ site.baseurl }}/media/si/new_SI.svg){: width=75% }

The diagram above shows interplay of the seven base units and the seven defining constants in the 2018 redefinition (Pisanty, 2018). Here the diagram shows the defining constants on the outside (in lighter colours), and the fundamental units within. Arrows point to the relationships between constants and units, and between fundamental units.

All other units then derive in a structured manner from either the fundamental units, or from other units. However in each unit the quantity value arises from the product of the unit and the numerical value of that unit. The SI unit structure is _coherent_ in that (SI Brochure, (2019), pg. 137)

> … equations between the numerical values of quantities take exactly the same form as the equations between the quantities themselves

Since the base SI units are now tied to physical constants, ['base' and 'derived' units]({{ site.baseurl }}//reference/si/units.html) behave in exactly the same way. However for historic reasons it has become common to distinguish between the two (SI Brochure, 2019. pg. 129).

## Units, Dimensions and Quantities

More formally, for all SI units the relationship between quantity value $$A$$, numerical value $$\left\{ A \right\}$$, and the unit $$\left[ A \right]$$ in SI is

$$A = \left\{ A \right\}\left[ A \right]$$

The relationship between these three entities above defines the whole SI system of units, and the expression of quantities within SI.

For example, the quantity value of velocity $$\nu$$ is physically defined by the relationship

$$\nu = \frac{l}{t}$$

where $$l$$ is the distance a particle in uniform motion with velocity $$\nu$$ travels in the time $$t$$. Note that this relationship holds _regardless of the unit system chosen_. The relationship between $$\nu$$, $$l$$ and $$t$$ is a property of the underlying physics _not_ the unit system chosen.

In SI the [_dimension_]({{ site.baseurl }}/reference/si/dimensions.html) of length $$l$$ is $$L$$, the dimension of time $$t$$ is $$T$$. The dimension of length $$L$$ has the metre (symbol m) as the [base unit]({{ site.baseurl }}/reference/si/units.html#base-quantities-and-units), and the dimension of time $$T$$ has the second (symbol s) as the base unit.

Units in SI are coherent, and thus follow the underlying relationships. Applying the unit metre for the dimension of length, and the unit second for the dimension of time gives the unit equation

$$\left[ \nu \right]_\text{u} = \frac{\left[ l \right]_\text{metre}}{\left[ t \right]_\text{second}}$$

Therefore the quantity value $$\nu$$ has the SI unit $$\left[ \nu \right]_\text{u}$$ or $$\frac{\text{metre}}{\text{second}}$$. Every unit within SI has an associated symbol, and hence this unit for $$\left[ \nu \right]_\text{u}$$ is equivalently expressed in symbols as $$\frac{\text{m}}{\text{s}}$$, $$\text{m} / \text{s}$$ or $$\text{m}\ \text{s}^{-1}$$.

Since $$ \nu = \left\{ \nu \right\}\left[ \nu \right]$$, $$ l = \left\{ l \right\}\left[ l \right]$$, and $$ t = \left\{ t \right\}\left[ t \right]$$, these measured numerical values and units then determine the quantity value for $$\nu$$ as

$$\left\{ \nu \right\}\left[ \nu \right]_\text{metre per second} = \frac{\left\{ l \right\}\left[ l \right]_\text{metre}}{\left\{ t \right\}\left[ t \right]_\text{second}}$$

or more conventionally in symbols as

$$\left\{ \nu \right\}\left[ \nu \right]_{\text{m}\ \text{s}^{-1}} = \frac{\left\{ l \right\}\left[ l \right]_\text{m}}{\left\{ t \right\}\left[ t \right]_\text{s}}$$

For a specific particle, experiments determine the numerical value $$\left\{ \nu \right\}$$, for the measured numerical values of $$\left\{ l \right\}$$ and $$\left\{ t \right\}$$. All measured numerical values are also expressed in the units $$\left[ \nu \right]_{\text{m}\ \text{s}^{-1}}$$, $$\left[ l \right]_\text{m}$$ and $$\left[ t \right]_\text{s}$$.

As a consequence of this fundamental relationship between quantity value, the numerical value and unit, changing the unit _also_ changes the expression for the quantity value. For example, using the [unit prefix]({{ site.baseurl }}/reference/si/prefixes.html) kilo (symbol k), to express the dimension $$L$$ in kilometre gives the quantity expression

$$\left\{ \nu' \right\}\left[ \nu' \right]_{\text{km}\ \text{s}^{-1}} = \frac{\left\{ l' \right\}\left[ l' \right]_\text{km}}{\left\{ t' \right\}\left[ t' \right]_\text{s}}$$

Since $$1\ \text{km} = 1 \times 10^{3}\; \text{m}$$, the two quantity expressions are relate to each other as

$$\left\{ \nu' \right\}\left[ \nu' \right]_{\text{km}\ \text{s}^{-1}} = \left\{ \nu \right\}\left[ \nu \right]_{\text{m}\ \text{s}^{-1}} \cdot 1 \times 10^{3}$$

or

$$\frac{\left\{ \nu' \right\}\left[ \nu' \right]_{\text{km}\ \text{s}^{-1}}}{1 \times 10^{3}} = \left\{ \nu \right\}\left[ \nu \right]_{\text{m}\ \text{s}^{-1}}$$

In both cases the fundamental relationship to the quantity value of $$\nu$$ remains coherent. However the _expression_ of that quantity value in the numerical value $$\left\{ \nu \right\}$$ (or $$\left\{ \nu' \right\}$$) and the unit value $$\left[ \nu \right]$$ (or $$\left[ \nu' \right]$$) changes as the unit values change.

## The 2018 Redefinition of the SI Units

Until the 2018 meeting of the [Bureau International des Poids et Mesures](https://www.bipm.org/en), the SI defined the fundamental units from a mixture of physical constants and external references. For example in 1983 the Seventeenth General Conference on Weights and Measures (CGPM) redefined the metre from a physical prototype to (SI Brochure, (2006), pg. 112)

> … the length of the path travelled by light in vacuum during a time interval of 1/299 792 458 of a second.

whereas the kilogram remained as (SI Brochure, (2006), pg. 112)

> the unit of mass; it is equal to the mass of the international prototype of the kilogram

The diagram below shows these external references before 2018 in grey, with the relationship shown between the seven base SI units in the centre (Pisanty, 2018). Note that unlike the modern SI, many of the fundamental units do not have a defined relationship between themselves.

![SI Unit Relations in the Old SI (Pisanty, 2018)]({{ site.baseurl }}/media/si/old_SI.svg){: width=75% }

The core task of the 'new SI' required a return to the fundamental relationship between quantities, numerical values and units

$$A = \left\{ A \right\}\left[ A \right]$$

For some fundamental units, such as mass, $$\left\{ A \right\}$$ in the relationship above depended on precise, repeatable measurements to determine the quantity value $$A$$. Other fundamental unit, such as the metre rearranged the quantity expression as

$$\frac{A}{\left[ A \right]} = \left\{ A \right\}$$

Here the numerical value of the constant defining the fundamental unit, $$\left\{ A \right\}$$ _is defined_ to have fixed value without uncertainty. For example the physical constant $$c$$ (the velocity of a photon in a vacuum) defines the metre. Using the definition of the metre from the Eighth Edition of the SI Brochure quoted above, this means the metre is also defined as

$$\frac{c}{\left[ \text{m}\ \text{s}^{-1} \right]} = \left\{ 299\, 792\, 458 \right\}$$

Tying the second to a physical constant in the same way, the Ninth Edition of the SI Brochure defines the metre as (SI Brochure, (2019), pg. 131)

> The metre, symbol $$\text{m}$$, is the SI unit of length. It is defined by taking the fixed numerical value of the speed of light in vacuum, $$c$$, to be $$299\ 792\ 458$$ when expressed in the unit $$\text{m}\ \text{s}^{−1}$$, where the second is defined in terms of the caesium frequency $$\Delta\nu_{\text{Cs}}$$.

Using numerical values close to values determined through careful experiments (to avoid the quantity value of the unit changing), gave the 'new SI' defined units in current use. This 'new SI' summarised in the diagram below, showing the new arrangement of physical constants and units (Pisanty, 2018).

![Interdependence of the Seven SI base Units and Defining Constants as their 2019 Redefinition (Pisanty, 2018)]({{ site.baseurl }}/media/si/new_SI.svg){: width=75% }

Note that _practically_ there should be no difference between the 'new SI' and 'old SI'. Careful measurement of the underlying phenomena has ensured a greater internal consistency, but also consistency with 'historic' units (Brown et al., 2021).

## References

* Brown, R. J. C., Brewer, P. J., Pramann, A., Rienitz, O. & Güttler, B. (2021). Redefinition of the Mole in the Revised International System of Units and the Ongoing Importance of Metrology for Accurate Chemical Measurements. _Analytical Chemistry_ [Online], 93 (36), pp. 12147–12155. Available from: <https://doi.org/10.1021/acs.analchem.1c02776>.

* _Emilio Pisanty_ (2018). SI Unit Relations. [[online](https://github.com/episanty/SI-unit-relations)].

* _SI Brochure: The International System of Units_ (SI) (2006). Bureau International des Poids et Mesures. Eighth Edition. [[online](https://www.bipm.org/en/publications/si-brochure)].

* _SI Brochure: The International System of Units_ (SI) (2019). Bureau International des Poids et Mesures. Ninth Edition. [[online](https://www.bipm.org/en/publications/si-brochure)].

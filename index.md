


(AnyExampleClass)=
# AnyExampleClass

<!-- The furo theme renders these over muliple lines. This is fixable with css -->
:Type: Creatable
:Parent class: [AnyKinMeasure](#AnyKinMeasureReal)
:Child classes: [AnyKinCom](#AnyKinCoM)


## Description

```{include} class-descriptions/AnyExampleClass.md
```




```{list-table} Demo examples related to AnyExampleClass
:widths: 40 60
:header-rows: 1
:class: plain

   * - Demo
     - Description
   * - `<some anylink stuff>`
     - Measuring the linear motion (translations).
```

## Expected members


:::{dropdown} [AnyRefFrame (1..2)]{.member-title}
:class-title: member-entries odd
:name: AnyClassExample.AnyRefFrame  <!-- This should create a linkable cross-reference target  -->

**Class type:**  [](#AnyRefFrame) \
**Number:** 1..2 \


The reference frames that define the vector

:::




## Required initialization members


:::{dropdown} [Type]{.member-title}
:class-title: member-entries odd
:name: AnyClassExample.Type  <!-- This should create a linkable cross-reference target  -->

**Class type:**  [AnyKinRotationalType](#AnyKinRotationalType) \
**Eval moment:** [Const](#InsideAMS_EvalMoments)

Coordinate type specification.

:::


## Optional initialization members

```````{dropdown} RefFrames
:class-title: member-entries odd
:name: AnyClassExample.RefFrames

**Class type:**  [AnyObjectPtr](#AnyObjectPtr) \
**Eval moment:** [Const](#InsideAMS_EvalMoments) \
**Default:** *Depends on other values* \
 \

Array of pointers to the reference frames (class AnyRefFrame and derived) that are basic input to the kinematic measure. Notice that some kinematic measures also use other reference frames implicitly.

```````




<!-- This represents a nested folder -->

:::::::::::{dropdown} [viewKinMeasure]{.member-title} [=]{.member-title-equal} [{...}]{.member-title-default}
:class-title: member-entries even
:name: AnyClassExample.viewKinMeasure


<!--  The Visible member is inside the viewKinMeasure dropdown -->
:::::::{dropdown}  [Visible]{.member-title} [=]{.member-title-equal} [Off]{.member-title-default}
:class-title: member-entries odd
:name: AnyClassExample.viewKinMeasure.Visible

**Class type:**  [](#AnySwitchVar) \
**Eval moment:** [RuntimeVar](#InsideAMS_EvalMoments) \
**Default:** `Off` \


Visibility setting, which specifies default visibility of the object.

:::{dropdown} Test of 3. level dropdown

with content

:::

:::::::

:::::::{dropdown} [Opacity]{.member-title} [=]{.member-title-equal} [1.0]{.member-title-default}
:class-title: member-entries even
:name: AnyClassExample.viewKinMeasure.Opacity

**Class type:**  [AnyVar](#AnyVar) \
**Eval moment:** [RuntimeVar](#InsideAMS_EvalMoments) \
**Default:** `1.0` \

Opacity setting, which specifies default opacity of the object.

:::::::


:::::::::::





## Denied-Access members

:::::::::::{dropdown} [UpdConfig]{.member-title}
:class-title: member-entries odd
:name: AnyClassExample.UpdConfig


**Class type:**  [AnyUpdVar](#AnyUpdVar)
**Eval moment:** [Const](#InsideAMS_EvalMoments)
**Default:** `0`

Counter of updates of configuration variables (i.e. the 'ConfigVar' Evaluation Moment).


:::::::::::



<!-- some dummy targets so links below doesn't fail -->

(AnyKinCoM)=
(AnyKinMeasureReal)=
(AnyObjectPtr)=
(InsideAMS_EvalMoments)=
(AnyKinRotationalType)=
(AnyRefFrame)=
(AnySwitchVar)=
(AnyVar)=
(AnyUpdVar)=

### dummy target
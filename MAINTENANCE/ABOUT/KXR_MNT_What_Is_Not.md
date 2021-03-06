---
title: What Isn't It ?
parent: About
grand_parent: Maintenance Editor
has_children: true
nav_order: 2
---

# **What Isn't Kalopsia XR - Maintenance Editor ?**
This is maintenance stuff training module of Kalopsia XR ecosystem.\
We are (absolutely) going to add new features and modules to our ecosystem for solving our customer's problems and targeting other technical departments.\
Also it is a fact that Kalopsia XR ecosystem has remarkable graphics thanks to its **Unreal Engine 4, Nvidia RTXGI and DLSS** based structure.

But our modules are not created with **visualization or marketing focused "render engine"** purposes like VRAY, Autodesk Arnold, Autodesk VRED, Marmoset Toolbag, Keyshot, Lumion or Twinmotion.

**For this reason, we deprecated these features. You can see additional explanations about relative feature.**
+ **Shadows.**
   - Simulation contents which created with this editor will be used mainly by **"blue-collar stuff"** and we noticed that these target users don't notice shadows at all in VR. So we disabled this feature for gaining extra software performance.

+ **Material Creation Editor.**\
*Material means visualized patterns of objects. For example, rust and/or roughness patterns can be considered as metal materials for objects.*
   - If we integrated an advance material creation editor (for example allowing its user to define PBR texture passes such as normal, metallic, roughness and etc.) we would increase it's learning curve.\
     For example, engineer should know how to Unwrap UV for their models and texture pass properties. Of course there are some auto-uw techniques but they can not work for every object or every usage.
   - Also we noticed that maintenance engineers who will build simulations, simply focus on **scenario creation and document  attachment functions.** They don't spend time to **create** materials.
   - If they want **customized** realistic materials, they can define them in Solidworks, Autodesk Inventor or 3Ds Max while drawing their models. All these softwares support PBR and KHR compatible material define functions in their latest versions.
   - If model file has realistic material, our software can import it very well.

+ **Light Properties Editor.**
   - As we say before, Kalopsia XR does not render shadows; reflections don't prevent its user to see objects and GI functions can lighten everywhere. Also we use cold-white light to get real color of objects. So, changing light functions will not increase its training or exploring features. For this reason we did not integrate a light editor.

**In the other hand, we have these graphics features**
+ We enabled **RTXGI and Ray Traced Reflections** because that blue-collar stuffs noticed reflections which give metallic looks to objects.
+ We integrated **photography snapshot function** for enabling its user to get some realistic machine state photos.
+ We integrated **pre-defined material assignment** editor. Engineers can not create a material from start but they can assign various materials from our library to their objects.

Even if we depreceted these features, we **have** their functions in our source code.\
So if we see necessity, **we can just integrate them in a short time.**

**In short, these deprecatations are not about our know-how.\
They are all about focusing its purpose and decreasing its learning curve. Faster simulation creation is better for our customer's ROI from Kalopsia XR ecosystem.\
We came these conclusions with our pilot applications in factories.**

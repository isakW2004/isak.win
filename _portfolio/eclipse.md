---
layout: project
title: Eclipse
tags: university industrial cad featured model
logo: /project-logos/eclipse.svg
image: /assets/project-images/eclipse.webp
desc: A bedside clock and lamp that uses motion and light to enhance the bedtime routine.
completed-date: Spring 2025
accent: rgba(78, 160, 100, 0.2)
rank: 1
---
<div class="project-overview">
    <h2 class="project-overview__title" >Project Overview</h2>
    <div class="project-overview__row">
        <div class="project-overview__metric">
            <h5 class="project-overview__metric-title">Prompt</h5>
            Use transformative motion in a lighting device or lamp.
        </div>
        <div class="project-overview__metric">
            <h5 class="project-overview__metric-title">Timeline</h5>
            <div>
            <span class="project-overview__metric-number">7</span>
            <span class="project-overview__metric-subtext">weeks</span>
            </div>
        </div>
        <div class="project-overview__metric">
            <h5 class="project-overview__metric-title">Skills Used</h5>
            <div class="project-overview__metric-chip-set">
                <div class="metric__chip">Research</div>
                <div class="metric__chip">Ideation</div>
                <div class="metric__chip">Model Making</div>
                <div class="metric__chip">Prototyping</div>
                <div class="metric__chip">SOLIDWORKS</div>
                <div class="metric__chip">Python</div>
                <div class="metric__chip">KeyShot</div>
            </div>
        </div>
        <div class="project-overview__metric project-overview__stacked">
            <div>
                <h5 class="project-overview__metric-title">Completed For</h5>
                University
            </div>
            <div>
            <h5 class="project-overview__metric-title">Project Type</h5>
                Freeform Skill Application
            </div>
        </div>
    </div>
</div>

# Research
I explored bedtime lighting for both adults and children, then identified opportunities to improve and adapt them to fit the requirements of this project.
<style>
    @media (min-width: 1200px) {
        .research-grid{
            grid-template-columns: 1fr 1fr;
            display:grid;
        }
    }
</style>
<div class="research-grid">
    <img class="transparent" alt="Research Section Part 1" src="assets/eclipse/research-1.webp">
    <img class="transparent" alt="Research Section Part 2" src="assets/eclipse/research-2.webp"> 
</div>

# Inspiration
Eclipse took early inspiration from several lighting devices functions, mechanisms, and expressive motifs.
<img alt="Inspiration boards" src="assets/eclipse/inspiration-board.webp" class="transparent">

# Ideation
![Early ideation sketches](assets/eclipse/ideation-compilation.webp)

# Early Form & Mechanism Models
These models tested the bellow mechanism and the explored forms that the light could take.
<div class="card-columns card-columns--mobile-double">
    <img alt="Prototype 1, a foam form model" src="assets/eclipse/early-prototypes/proto-1.webp">
    <img alt="Prototype 2, a cardboard mechanism test" src="assets/eclipse/early-prototypes/proto-2.webp">
    <img alt="Prototype 3, a cardboard exploration of another form" src="assets/eclipse/early-prototypes/proto-3.webp">
    <img alt="Prototype 4, a foam form model" src="assets/eclipse/early-prototypes/proto-4.webp">
    <img alt="Prototype 5, a foam form model" src="assets/eclipse/early-prototypes/proto-5.webp">
    <img alt="Prototype 6, a 3d-printed mechanism test with added clearance for a mechanism" src="assets/eclipse/early-prototypes/proto-6.webp">
</div>

# Early SOLIDWORKS Models
Based on ideation and early models, I started prototyping iteratively with CAD and 3D printed parts. These models revealed problems that needed to be addressed, like skipping gear teeth.
<div class="card-columns card-columns--mult-2">
    <div class="card">
        <img src="assets/eclipse/early-cad/v3-form.webp">
        <div class="card__content">
            <h3>Model 1</h3>
            Form & mechanism development 
        </div>
    </div>
    <div class="card">
        <img src="assets/eclipse/early-cad/v3-clearance.webp">
        <div class="card__content">
            <h3>Model 1</h3>
            Mechanism tolerance view
        </div>
    </div>
    <div class="card">
        <img src="assets/eclipse/early-cad/v4-full.webp">
        <div class="card__content">
            <h3>Model 2</h3>
            Mechanism and assembly improvements & rotary knob
        </div>
    </div>
    <div class="card">
        <img src="assets/eclipse/early-cad/v4-gear.webp">
        <div class="card__content">
            <h3>Model 2</h3>
            View of servo and larger gear teeth
        </div>
    </div>
</div>

# Result
<div class="card-columns">
    <img alt="Front View" src="assets/eclipse/hero.webp">
    <img alt="Rear View" src="assets/eclipse/back.webp">
    <img alt="Knob Detail View" src="assets/eclipse/knob.webp">
    <img alt="In-Use View" src="assets/eclipse/in-use.webp">
    <img alt="Side-by-side with code" src="assets/eclipse/with-code.webp">
    <img alt="Context Shot" src="assets/eclipse/context.webp">
</div>
The bellows were excluded from the final model last-minute. The hub of the mechanism was larger than what the early prototypes tested. This unexpectedly caused the bellows to strain and pull over the hub when opened, and crumple when closed.

# A Look Inside
![Exploded Render](assets/eclipse/exploded.webp)

<p>
    <video autoplay muted loop playsinline style="pointer-events:none" aria-desc="Internal View Animation">
        <source src="assets/eclipse/anim.webm" type="video/webm">
        <source src="assets/eclipse/anim.mp4" type="video/mp4">
    </video>
</p>

![Technical Drawing and BOM](assets/eclipse/tech-drawing.webp)
The Eclipse model is based on Raspberry Pi, using a rotary endoder for input, a servo for hand movement, a programmable light strip, and a speaker. The clock mechanism is an off-the-shelf component.
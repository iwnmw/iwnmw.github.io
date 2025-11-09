# Finite Element Knee Models (Summer of 2023)

I conducted an undergraduate research project with Dr. Antonis Stylianou at UMKC to investigate the effects of the adolescent growth plate on ACL stress/strain during knee loading.

<!-- Model Introduction Section -->
<div style="display:flex; gap:20px; margin-bottom:30px; align-items:stretch;">
  
  <!-- Text -->
  <div style="flex:1; min-width:0;">
  <p>
    I had a number of responsibilities over the summer. I began by assembling two knee models using geometries provided by Dr. Stylianou. The first knee represented an "adult" knee, in which the growth plate was not included, and the femur and tibia were a single, solid bone. The second knee represented an adolescent knee, which included growth plates that separate the tibia and femur into distal and proximal sections. A screenshot of this model is shown in Figure 1!

Next, with the geometries in place, I was responsible for setting up both the "growth plate" model and the "non-growth plate" model. This included defining material properties for the various objects present in the models (bones were modeled as rigid bodies, cartilage and the growth plates were modeled as Mooney-Rivlin hyperelastic materials, and ligaments were modeled as transversely isotropic, fibrous Mooney-Rivlin materials (values for these material models have been experimentally determined in the literature). This also included meshing each geometry and defining contacts (rigid contacts were used between bones and their connected cartilage and sliding contacts between contacting cartilage). Finally, boundary conditions had to be determined, and due to initial convergence issues, I worked with Dr. Stylianou to simplify boundary conditions to reduce the computational expense.

Finally, with both models set up, I was responsible for defining and running a series of four simulations on each model. Anterior tibial translations of 7mm and interior tibial rotations of 5 degrees were applied to both models, and "loaded" and "unloaded" versions of both motions were applied as well ("loaded" simulations were simulations in which a 250N downward force was applied to the femur, representing the compression of the knee due to bodyweight, and "unloaded" simulations did not contain this additional load force). This led to four different quasi-static simulations for each model, for a total of eight simulations.
  </p>
  </div>
  
  <!-- Image -->
  <div style="
    flex: 0 0 45%; 
    max-width: 45%; 
    display:flex; 
    justify-content:center; 
    align-items: center;
    flex-direction:column;
    ">
   <img src="../assets/images/GPKneeModel.png"
      style="width:100%; height:auto; border-radius:8px; border:1px solid #ddd;">
    <p style="text-align:center; font-size:0.9em; color:#666; margin-top:8px">
      Figure 1. Knee Model (With Growth Plate)
    </p>
  </div>
</div>

<!-- Capitol Picture Section -->
<div style="display:flex; gap:20px; margin-bottom:30px; align-items:stretch;">
  <!-- Image -->
  <div style="
    flex: 0 0 45%; 
    max-width: 45%; 
    display:flex; 
    justify-content:center; 
    align-items: center;
    flex-direction:column;
    ">
   <img src="../assets/images/CapitolPoster.jpg"
      style="width:100%; height:auto; border-radius:8px; border:1px solid #ddd;">
    <p style="text-align:center; font-size:0.9em; color:#666; margin-top:8px">
      Figure 2. Missouri Capitol Poster Presentation
    </p>
  </div>

  <!-- Text -->
  <div style="flex:1; min-width:0;">
  <p>
    After setting up and running the simulations, I was responsible for recording, documenting, and presenting the results of the analyses. I presented my findings at UMKC's undergraduate research symposium, and was then selected to present my findings at the Missouri State Capitol. Both presentations were a poster presentation format. Figure 2 is a picture of me standing next to my poster at Missouri's Undergraduate Research Day at the Capitol!
  </p>
  </div>
</div>

---

## 🚀 Projet : Cerebellum Clonal Analysis
**11 notes pertinentes**

### 📅 Frise chronologique des avancées

```mermaid
timeline
    title Avancement
        section Cerebellum Clonal Analysis
            18 Dec : Analysis of 3D data from Brainbow samples, focusing on the f
        section Cerebellum Clonal Analysis
            16 Dec : The user is working on a study analyzing cerebellum cells us
        section Cerebellum Clonal Analysis
            19 Jan : The meeting discussed the cerebellum project. The focus is o
        section Cerebellum Clonal Analysis
            ??? : This note focuses on the analysis of cerebellar clonal data 
        section Cerebellum Clonal Analysis
            ??? : Title - Uncovering the dynamics of cerebellar clonal expansi
        section Cerebellum Clonal Analysis
            ??? : Struggling with the P21 problem in the cerebellum clonal ana
        section Cerebellum Clonal Analysis
            ??? : The user has been debugging their code related to the segmen
        section Cerebellum Clonal Analysis
            ??? : The user is working on the extraction of 44 points from a ma
        section Cerebellum Clonal Analysis
            ??? : User is facing issues with the connection, focusing on clona
        section Cerebellum Clonal Analysis
            ??? : The user is encountering issues with the script `step_3_fuse
```

### 📝 Détail des entrées

#### **18/12/2025** – notes 18 dec

**Résumé :**
- Analysis of 3D data from Brainbow samples, focusing on the "fingers" clones (2 zones green vs 3-4 zones purple) observed visually.
- Neighbor analysis in 3D using k-nearest neighbors and distance metrics.
- Comparison of color spaces 3D revealing that HSV provides the greatest distinction between border and Purkinje cells.
- Spatial gradient analysis showing strong correlation between adjacent regions (r = 0.628) and a higher similarity ratio for adjacent zones (4.74x).
- Biological results confirming clonal grouping in both populations, strong spatial gradients, and coherent 3D organization.
- Optimization approach developed to identify the "fingers" clones based on hierarchical clustering and spatial coherence.
- Validation of biological findings with anatomical correspondence aligning with cerebellar fissures and organization along lobule axes.

**Mots-clés :** `3D analysis, Brainbow, Clonal analysis, Color clustering, K-nearest neighbors, HSV color space, Spatial gradient, Anatomical correspondence`

**✅ Prochaines étapes :**
- [ ] Further optimization of the "fingers" clones identification pipeline.
- [ ] Validation and interpretation of developmental implications.
- [ ] Address connectivity issues with SSH and version control conflicts.

---

#### **16/12/2025** – notes 16 dec

**Résumé :**
- The user is working on a study analyzing cerebellum cells using Brainbow, specifically focusing on cluster analysis and color clustering. The data shows significant clonal grouping for granular cells compared to Purkinje cells. However, there seems to be an issue with the code used and a need to re-evaluate the methodology or metrics.

**Mots-clés :** `Cerebellum cells, Brainbow, cluster analysis, color clustering, Purkinje cells, granular cells, RGB distance, HSV coherence`

**✅ Prochaines étapes :**
- [ ] Correct the error in loading the Purkinje data.
- [ ] Reevaluate the methodology and metrics used for analysis.
- [ ] Identify specific zones in the fingers for better clustering results.
- [ ] Compare the results between granular and Purkinje cells again after correcting the error.

---

#### **19/01/2025** – Notes19 janv

**Résumé :**
- The meeting discussed the cerebellum project. The focus is on exploring layers in granular cells but not in Purkinje cells. The CAGCRE (Rapid Cerebellar Anatomy and Connectivity Reconstruction) project needs to be continued quickly. After the meeting, repositories related to the paper should be tidied up, and points discussed with Anatole.

**Mots-clés :** `cerebellum, layers, granular cells, Purkinje cells, CAGCRE, rapid reconstruction, anatomy, connectivity, discussion, repository`

**✅ Prochaines étapes :**
- [ ] Continue CAGCRE project
- [ ] Tidy up repositories related to the paper
- [ ] Discuss points with Anatole
- [ ] Explore layers in granular but not Purkinje cells

---

#### **Date inconnue** – Untitled

**Résumé :**
- This note focuses on the analysis of cerebellar clonal data using Brainbow technique for cell lineage tracing and subsequent clustering to understand the developmental dynamics.

**✅ Prochaines étapes :**
- [ ] Further exploration of the clonal relationships in various regions of the cerebellum for a comprehensive understanding of its structural and functional organization.
- [ ] Investigation of possible links between the identified patterns and neurological diseases, potentially leading to novel therapeutic strategies.

---

#### **Date inconnue** – Untitled

**Résumé :**
- Title: "Uncovering the dynamics of cerebellar clonal expansion"
- The study employs Brainbow methodology for multi-color labeling in mouse cerebella to investigate clonal populations.
- Highlights: Analysis using clustering algorithms to categorize and quantify clonally related Purkinje cells, providing insights into the spatiotemporal dynamics of clonal expansion.
- Reflection: The findings offer a foundation for understanding the developmental processes in the cerebellum and could potentially aid in addressing neurological disorders linked to abnormal cerebellar development.

**✅ Prochaines étapes :**
- [ ] Further validation of the results using other animal models or techniques.
- [ ] Investigation of the molecular mechanisms underlying cerebellar clonal expansion.
- [ ] Exploration of the implications of these findings for neurological disorders associated with abnormal cerebellar development.

---

#### **Date inconnue** – notes 20 avril

**Résumé :**
- Struggling with the P21 problem in the cerebellum clonal analysis project, specifically with the fusion of yellow cells. The current solution seems unsuccessful.
- Launched a script comparing several algorithms and configurations on section 22.
- Planning to re-run the deformation on sections with binning correction.
- Problem: insufficient storage space.
- Intend to perform classification, create multiple CSV files, and visualize directly.

**Mots-clés :** `P21 problem, Yellow cells fusion, Algorithms comparison, Deformation, Binning correction, Classification, CSV files, Visualization`

**✅ Prochaines étapes :**
- [ ] Address the issue with the P21 problem by improving the fusion of yellow cells.
- [ ] Implement the planned deformation with binning correction.
- [ ] Perform classification, create CSV files, and visualize the results for further analysis.

---

#### **Date inconnue** – Untitled

**Résumé :**
- The user has been debugging their code related to the segmentation of cerebellum cells using a two-step pipeline (unsupervised clustering + CNN refinement). Initially, the segmentation performed well on 2D images but failed when applied to 3D volumes due to issues with the loading and saving of the model. After debugging, it was found that the problem lay in the 3D segmentation pipeline's preprocessing steps rather than the model loading. A new script (segment_all_3d_clean.py) has been implemented that trains the model for each execution, applies it to 3D volumes, and uses the same preprocessing functions as during training to produce quality equivalent masks.

**Mots-clés :** `cerebellum cells, segmentation, CNN refinement, 2D images, 3D volumes, preprocessing pipeline, DINOv3 features, unsupervised clustering, deepseek`

**✅ Prochaines étapes :**
- [ ] Test the new script (segment_all_3d_clean.py) on larger datasets and evaluate its performance compared to other segmentation methods like Unet.
- [ ] Investigate the reasons for large variations in the results obtained with Unet.

---

#### **Date inconnue** – 11 fev

**Résumé :**
- The user is working on the extraction of 44 points from a master curve related to CAGCRE data. The points have been saved in a file located at /home/giraud/Documents/LOB/Cerebellum/surface_extraction/clicked_points.pkl. The user mentions having issues with stitching and has copied sections 16 and 18 from a previously saved stitching for further analysis, which is stored in the directory sauvegarde_11_02. The user seems to be considering performing classification on the CAGCRE data.

**Mots-clés :** `CAGCRE, points extraction, master curve, stitching, classification`

**✅ Prochaines étapes :**
- [ ] Perform classification on the extracted CAGCRE data for further analysis.
- [ ] Continue working on the stitching issue and improve the quality of the stitched images if necessary.
- [ ] Save and manage the data in appropriate directories for future reference.

---

#### **Date inconnue** – notes 10 fev

**Résumé :**
- User is facing issues with the connection, focusing on clonal analysis for cerebellum cells in the meantime.
- Comparison of Purkinje cells with granular internal cells is needed, and problematic zones should be removed.
- A cluster of granular external cells is to be taken, followed by selecting the color region and checking all cells within it, ensuring they are at the border.
- The segmented Purkinje cells will be checked if there's a change in color using Biapy, as the cells seem more ellipse now.
- Statistics of colors outside the sample need to be revisited.
- All studies related to presentation but with smaller Z should be resumed from the given notebook.

**Mots-clés :** `Cerebellum clonal analysis, Purkinje cells, Granular internal cells, Connection issues, Segmentation, Biapy, Color clustering, Stats colors, Presentation, Z`

**✅ Prochaines étapes :**
- [ ] Resolve the connection issue.
- [ ] Compare and segment Purkinje cells with granular internal cells.
- [ ] Remove problematic zones from the comparison.
- [ ] Check a cluster of granular external cells, focusing on the color region and cells at the border.
- [ ] Verify if there's a change in color for Purkinje cells using Biapy.
- [ ] Analyze statistics of colors outside the sample.
- [ ] Revisit all studies related to presentation with smaller Z.

---

#### **Date inconnue** – notes 5 fe

**Résumé :**
- The user is encountering issues with the script `step_3_fuse_sections_Numpy_Dask_Zarr.py` in the Cerebellum clonal analysis project related to index errors, incorrect link parameters, and the need for increased parameters. There seems to be a discussion about automating this issue.

**Mots-clés :** `step_3_fuse_sections_Numpy_Dask_Zarr.py, IndexError, parameter adjustment, automation, Cerebellum clonal analysis`

**✅ Prochaines étapes :**
- [ ] Fix the index error and correct link parameters.
- [ ] Consider increasing other parameters to improve results.
- [ ] Investigate potential solutions for automating the script execution process.
- [ ] Test the updated script on a smaller dataset before running it on the entire project.
- [ ] Consult with team members if necessary to troubleshoot any issues or gain insights for improving the script.

---

#### **Date inconnue** – 3 décembre

**Résumé :**
- Resumed the classification code for the Cerebellum clonal analysis project.
- Encountered an issue with Purkinje cells and data treatment (incorrect normalization).
- Issue resolved by fixing a typo in data types (uint16 vs float32).
- Cleaned up ISBI related codes.
- Request for access from Laure, but no Christmas gift ideas yet.

**Mots-clés :** `Cerebellum clonal analysis, Purkinje cells, Data normalization, Code cleanup (ISBI), Access request (Laure)`

**✅ Prochaines étapes :**
- [ ] Continue working on data treatment and plot generation for the Cerebellum clonal analysis project.
- [ ] Evaluate the effectiveness of the corrected code.
- [ ] Collaborate with Laure if access is granted.
- [ ] Brainstorm Christmas gift ideas.

---

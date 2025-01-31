---
layout: page
title: Peptide-based
permalink: /tools/peptide-based/
---

<!-- Ensure Bootstrap is loaded
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"> -->

<section id="programs" class="programs">
    <div class="container">
        <div id="Peptide-based" class="custom-row">
            <!-- First Box -->
            <div class="custom-box">
                <h4><a href="https://balalab-skku.org/mHPpred/" target="_blank" rel="noopener noreferrer" class="text-success">mHPpred</a></h4>
                <p>Hormone peptides predictor</p>
            </div>
            <!-- Second Box -->
            <div class="custom-box">
                <h4><a href="https://balalab-skku.org/mACPpred2/" target="_blank" rel="noopener noreferrer" class="text-success">mACPpred 2.0</a></h4>
                <p>Anticancer peptides predictor</p>
            </div>
        </div>
    </div>
</section>

<style>
    /* Ensure the main content is aligned to the left */
    .programs .container {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
    }

    /* Adjust heading to align left */
    h1 {
        text-align: left;
        margin-bottom: 20px;
    }

    /* Box styling */
    .custom-box {
        width: 320px; /* Increase size */
        height: 200px; /* Increase height */
        padding: 20px;
        border: 1px solid #ddd;
        border-radius: 10px;
        box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        text-align: center;
        display: flex;
        flex-direction: column;
        justify-content: center; /* Center vertically */
        align-items: center; /* Center horizontally */
    }

    /* Row container to hold boxes and align them left */
    .custom-row {
        display: flex;
        gap: 40px; /* Space between boxes */
        margin-left: -20px;
    }
</style>
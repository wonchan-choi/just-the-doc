---
title: Home
layout: home
---
<style>
  /* Default styles */
  .flex-container {
    background-color: #F5F6FA;
    padding: 20px;
    display: flex;
    align-items: center;
  }

  /* Image styles for small screens (up to 767px width) */
  @media (max-width: 767px) {
    .flex-container {
      flex-direction: column; /* Stack items vertically */
      align-items: center; /* Center items horizontally */
    }

    .flex-container img {
      width: 100%; /* Make the image take up the full width */
      margin-bottom: 15px; /* Add some space below the image */
    }
  }
</style>

<div class="flex-container">
  <div style="flex: 1;">
    <img src="/assets/images/wchoi_gp_60.png" alt="Wonchan Choi">
  </div>
  <div style="flex: 2; padding-left: 20px;">
    <!-- Your content here -->
    Assistant Professor<br>
    <a herf="https://uwm.edu/informationstudies/">School of Information Studies</a>, Univeristy of Wisconsin-Milwaukee
    <ul>
    <li>Email: wchoi@uwm.edu
    <li>Office: Northwest Quadrant Building D, Room 2890
    <li>Pronouns: he/him/his
    </ul>
    <button type="button" name="button" class="btn">CV</button>
    <button type="button" name="button" class="btn">Google Scholar</button>
  </div>
</div>
 


## Contact Information
Email: wchoi@uwm.edu
[Google Scholar](https://scholar.google.com/citations?user=p5_1GbgAAAAJ&hl=en)
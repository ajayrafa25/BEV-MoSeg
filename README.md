
<html>
<head>
  <title>BEV-MoSeg: Segmenting Moving Objects in Bird’s Eye View</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      line-height: 1.5;
    }

    h1 {
      text-align: center;
    }

    h2 {
      text-align: center;
      font-size: 1.2em;
      margin-top: 40px;
    }

    p {
      text-align: justify;
    }

    .news-item {
      margin-bottom: 10px;
    }

    .video-container {
      text-align: center;
    }

    .video-container h2 {
      margin-bottom: 0;
    }

    .video-container img {
      display: block;
      margin: 0 auto;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1 style="background-color: #90EE90;">BEV-MoSeg: Segmenting Moving Objects in Bird’s Eye View</h1>
  <h1><font size="3">Ajay Kumar Sigatapu, Venkatesh Satagopan, Ganesh Sistu, Ravikant Singh, AV Narasimhadhan</font></h1>

  <hr>

  <p><strong>Abstract:</strong> Moving object detection is a critical task for autonomous vehicles. As dynamic objects represent a higher collision risk than static ones, our own ego-trajectories have to be planned attending to the future states of the moving elements of the scene. Motion can be perceived using temporal information such as optical flow. In this work, we propose a new end-to-end architecture to detect moving vehicles in the Bird's eye view representation. The core idea behind our approach is to get the bird's eye view representation first and then detect the moving vehicles using either Correlation or Cross-Attention. We demonstrate the impact of our algorithm on the nuScenes dataset. To the best of our knowledge, there has been limited or no prior research conducted on this particular topic. In this work, we introduce a novel contribution to the field of moving object segmentation on the nuScenes dataset. We have generated custom labels that accurately annotate moving objects, which were not previously available. These labels enhance the dataset's utility for precise analysis and understanding of moving objects. To promote reproducibility, we will release the code used for generating these labels to the research community, allowing for further exploration and advancements in this area. We achieved an IoU Score of 26 percent.</p>

  <hr>

  <h2>News</h2>
  <div class="news-item">
    <p>[May 2023] Code coming soon  <a href="https://github.com/ajayrafa25/BEV-MoSeg">GitHub</a></p>
  </div>

  <hr>

  <h2>Results</h2>
  <img src="Results/eval000017032 (1).jpg" alt="Results">

  <hr>

  <div class="video-container">
    <h2><font size="3">Inference Video (CLICK ON THE IMAGE TO START VIDEO)</font></h2>
    <a href="https://www.youtube.com/watch?v=a1jQoD-EcfU">
      <img src="https://img.youtube.com/vi/a1jQoD-EcfU/0.jpg" alt="Video Thumbnail">
    </a>
  </div>


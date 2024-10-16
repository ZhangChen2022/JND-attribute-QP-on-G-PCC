# Analysis of Relationship between Point Cloud Just Noticeable Difference and Attribute Quantization Parameters


# Introduction:

Utilizing just noticeable difference(JND) thresholds to describe distortion visibility enables efficient transmission and storage of point clouds while maintaining high quality. Therefore, describing the relationship between point cloud JND and attribute quantization parameters (QP) is essential. This relationship is ,however, not clear regarding point cloud compression so far. We investigate the correlation between JND and attribute QP using Geometry-based Point Cloud Compression(G-PCC), which is the latest standard for point cloud compression. Moreover, we provide the corresponding datasets in this work. Using the K-means clustering algorithm, we partition the collected raw data into intervals and identify the peaks closest to the means in each sub-interval as the desired JND points. For human-content point clouds, although the number of JND varies, the QP values corresponding to different levels of JND show a regular distribution. The study focuses on the QP corresponding to the starting JND point(JND\textsubscript{S}) and the ending JND point (JND\textsubscript{E}).The findings indicate that the critical points for human-content point clouds are relatively consistent, with JND\textsubscript{S} mainly concentrated at $\text{QP = 27}$ and  JND\textsubscript{E} at $\text{QP = 45}$. Conversely, perception in object-content point clouds is more influenced by their content, and the distribution of JND is not as uniform as in human-content point clouds. 


# The experimental datasets and research results are accessible here.
Datasets link: (Different_AttrQp_Dataset.zip) https://pan.baidu.com/s/10xQmHnDJ5G9ccYt0icyblQ?pwd=j1pv 



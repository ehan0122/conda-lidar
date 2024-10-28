# conda-lidar
 Using these commands we will be able to process PCAP data from Velodyne Lidar VLP-16 and visualize it from bash using Python


# 1.) Download Conda
 First downnload Anaconda or Miniconda from the website and install it to your workspace. 
	<br />If you have a problem with running the shell, run this command to make the shell file executable
 <br /><br />`chmod +x 'Anaconda...sh'`
 <br /><br />and you can run the command by add `./` to your shell
 <br /><br /> `./Anaconda...sh`

# 2.) Create a New Conda Environment
Create a new Conda Environment to manage dependencies and avoid conflicts
<br /><br />`conda create -n lidar_env python=3.9`
<br />`conda activate lidar_env`

# 3.) Install Required Packages
Downalod Open3D, a library to process and visualize 3D data
<br /><br />`conda install -c conda-forge open3d`
<br /><br /> To parse PCAP data we will need to download velodyne library
<br /><br /> `pip install velodyne_decoder`

<br /><br /> Depending on the velodyne data you will need to download different libraries for each data type

# 4.) Load and Visualize Velodyne Data

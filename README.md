# N64-Buddy-Breakout
An AV breakout board to be used with the Tim Worthington N64 RGB mod. This board is designed in a way that provides pads on the edge of the multiout giving a nice clean finish and avoids soldering directly to the pins. The pad order matches TW's pads on the mod board, so using a ribbon cable is beneficial.

The breakout board also has two jumper pads - J1 and J2. These are used to route the SYNC to one of two pins. J2 will route SYNC to the SYNC pin of the AV Multiout. This will be the most common setting for most users. Even if you are using HDRV cables, you will likely still use this jumper setting. J1 is used if you need the SYNC to run to composite video (CV). This is not normally selected and is only used if you have previously disabled composite video for some reason.

J1: Sends SYNC to Composite Video (V) - Not Common Setting<br>
<b>J2: Sends SYNC to SYNC (S) - Most Common Setting</b>

# PCB Fabrication
Download GERBER Zip from above folder and upload it to your favorite PCB manufacturer

Board Thickness: 0.8mm

OshPark: https://oshpark.com/shared_projects/59MSjOS4 <br>
Project Link: https://oshwlab.com/fragolroc/n64rgb-buddy-board

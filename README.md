https://universe.roboflow.com/basketball-yolo-dataset/basketball-yolo-dataset/dataset/1?utm_source=copilot.com

Using this for one possible dataset. It's a pretrained basketball dataset.

1. I imported yolov8 and trained it on a dataset that i made with about 180 basketball images, and then trained it with an opens source dataset with around 300.

2. I had it detect the players, ball, and basket but for the purposes of this final i only keep the ball and basket

3. Drew a box at the top of the rim so i can use it for determing if the ball went in the hoop or not.

4. Created an interpolating polynomial to make a line using points the ball was at to see if the ball goes in the hoop

5. Determine if it goes in the hoop and update score

6. Talk about errors, false positives and ideas that might help
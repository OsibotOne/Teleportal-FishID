## **Detection Method**

A fish is determinded to be detected in the training data if:

1. Is closer than 2 meters from underwater robot.
2. The entire fish is in the frame.
3. Their are no compression artifacts on the fish.
4. The fish is at a good viewing angle (side or 45deg)
5. There is enough pixels to allow for a detection.
6. The bounding box does not include another fish.
7. There is not another fish infront or directly behind the fish.
8. Is a common fish species likley to be seen on most dives.

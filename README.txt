DarkLens – Test-site explorer
=============================
Double-click index.html (opens in your browser, works offline).

Overview tab  : results for all 30 test websites in one table.
Inspect a site: pick a website on the left, pick a journey (J1-J18), and step
                through its pages. Red boxes = DarkLens detections, dashed green
                = ground truth. Right panel shows findings, severity, CCPA clause,
                and whether each finding is correct.
Tip: open a journey tagged FU, go to page 1 and press "Reload page" – the fake
     countdown restarts from the same time (that is how DarkLens catches it).

Folder "sites" contains the 30 synthetic websites (540 journeys, 2,359 pages).
Each site was scored by a model trained without that site (5-fold cross-validation).

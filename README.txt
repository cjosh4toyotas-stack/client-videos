VECTOR VX — client-videos files

make-link.html
  Your Vector VX link builder. Now also keeps storage in check:
  after every upload it checks the bucket, and if it is over 9 GB
  (the free plan allows 10 GB) it deletes the oldest videos first
  until it is back under. The video you just uploaded is never touched.
  The current usage shows next to "Storage connected on this device".

watch-VECTOR-VX-SCENE.html
  Client page, style 1: the Vector VX corridor scene, video only,
  no words or buttons except the watermark on the video.

watch-SPACE-GRID.html
  Client page, style 2: Header, name, title, Call/Text buttons,
  large player, blue grid running out to a space horizon.

To use a client style: pick one, rename it to  watch.html  and put it
in the GitHub repo (cjosh4toyotas-stack/client-videos) in place of the
old watch.html. Only one watch.html can be live at a time.

index.html / views.html
  Landing page and view tracker, rebranded Vector VX (no McGrath).

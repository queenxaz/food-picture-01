# Tiny Chefs, Giant Feast

Three tiny chefs grill one giant glistening steak.

A single hero dish fills the frame: one giant steak on a grill, glossy with
sauce, steam rising, three miniature chefs in white hats tending it — warm
golden light, rich brown and amber tones. Made to make you hungry at a glance.

The concept follows the winning formula found by studying the top entries of
the earlier image bounties: a clear concept (tiny chefs + one giant dish)
beats a generic beautiful food photo.

The entry program writes the image to `/output/entry.png` deterministically:
the image bytes are embedded in `main.py` as a single-line base64 string and
decoded at runtime. No network, no randomness, no model calls. Embedding the
bytes in the program keeps it self-contained, and the output is byte-identical
to the image the concept was built around.

The image is an AI-generated image made for this entry (not a photograph):
a single 1024x1024 JPEG (written as `entry.png`, as the rules allow — the file
is told apart by its first bytes), 316,551 bytes. It was generated with
Leonardo AI (model Lucid Origin, seed 1571375497) in a single generation
costing 8 tokens, from a prompt for tiny miniature chefs grilling a giant
glistening steak, warm light, steam and a rich warm palette.

Built for the make.fun competition food-picture-01 ("Make the best-looking
food picture"), which opened 14 November 2026.

The program's output was verified byte-for-byte against the source file
before this entry was bundled, so the program's output is identical to the
image the concept was built around.

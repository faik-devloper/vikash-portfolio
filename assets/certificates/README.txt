CERTIFICATES — HOW TO ADD YOUR OWN
=================================

STATUS: DONE — all three slots are filled with Vikash Babu's own
documents and are published in the Certificates section:

      certificate-1.jpg  Provisional Certificate — Secondary School
                         Examination 2024 (Bihar School Examination Board)
      certificate-2.jpg  Mark Sheet — Secondary School Examination 2024
                         (Bihar School Examination Board)
      certificate-3.jpg  Kushal Yuva Program (KYP) Certificate, passed on
                         27 August 2024, generated 3 September 2024
                         (State Council for Vocational Training / Bihar
                         Skill Development Mission, Government of Bihar)

TO REPLACE ONE LATER
--------------------
1. Drop the new scan into this folder using the SAME filename
   (certificate-1.jpg, -2.jpg or -3.jpg) so no HTML change is needed.

2. If you add a fourth one, add certificate-4.jpg and copy one more
   <figure class="card cert-item"> block in index.html.

3. Format that fits the site:
      - JPEG (.jpg) is the format the CSS expects (--paper background,
        object-fit: contain, 220px tall card).
      - Landscape scans read best; portrait scans are letterboxed by
        object-fit: contain, never cropped.
      - Keep each file under ~350 KB so the page stays fast on mobile.
      - PNG works too — just use certificate-1.png and update the src.
      - PDF is NOT displayed by the site; convert the PDF to JPG first.
      - Put the file right-side up. If a scan is stored upside-down,
        rotate it before copying it in — CSS will not flip it for you.

4. Never publish a certificate that is not his, and never edit a
    certificate image to change a name or any mark.

WHAT TO CHECK AFTER SWAPPING
----------------------------
index.html, Certificates section: update the <img> src (only if the
extension changed), the width/height attributes to the real pixel size
(they prevent layout shift), the alt text and the <figcaption>.
No CSS or JS changes are needed.

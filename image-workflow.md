# Mandatory Image Workflow

1. Extract requirements and exact text.
2. Inspect and classify reference assets.
3. Perform feasibility, risk, and format analysis.
4. Select visual style (see `styles/style-catalog.md`) and art direction.
5. Select supported model, ratio, and the highest supported native resolution.
6. Declare the realism level (photoreal / cinematic-real / stylized). Apply scene discipline: one hero subject, at most three supporting elements.
7. Complete the Specification Lock: every subject, environment, camera, lighting, and material made specific; vague words replaced.
8. Write the production prompt and relevant negative constraints; run the pre-flight prompt review.
9. Check tool limits and costs.
10. Generate and wait for completion.
11. Inspect the actual output, including 100% zoom on faces, hands, text, and edges.
12. Evaluate brief compliance, craft, technical integrity, pixel clarity, and content integrity.
13. Diagnose defects and apply targeted corrections. Do not deliver known fixable defects.
14. If the image is under the 2048 px long-edge baseline, upscale it with a real supported tool; never relabel resized pixels as native. If the baseline cannot be reached, mark the resolution gate failed and report the exact size.
15. Inspect the final file and measure real dimensions and file type.
16. Deliver with the mandatory Image Production Report, including Generation Method & Provenance (final prompt, parameters, attempts, post-processing).

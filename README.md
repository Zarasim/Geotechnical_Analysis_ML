# Geotechnical_Analysis_ML
Classification task for cone penetration test (CPT) data.

The goal of this work is to determine from the cone-penetrometer testing (CPT) dataset which
unmarked (‘-’) entries might be close to a sample of a problematic material. If a row is within
20 cm of that material, the Near Material mark is set to ‘y’. Some samples contain none of that
material, and so rows within 20 cm of those samples are marked with ‘n’. The ‘-’ rows may or may
not contain this material as no samples were taken near these locations.

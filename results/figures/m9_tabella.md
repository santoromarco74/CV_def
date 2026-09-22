| esperimento | matcher | config                        | prove | successo_pct | rmse_m_mediano_ok | inlier_ratio | match_mediani | t_ms |
|-------------|---------|-------------------------------|-------|--------------|-------------------|--------------|---------------|------|
| E1          | loftr   | none / homography             | 80    | 42.5         | 0.053             | 0.622        | 1033          | 3875 |
| E1          | orb     | none / homography             | 112   | 67.9         | 0.113             | 0.741        | 2557          | 96   |
| E1          | sift    | clahe / homography            | 112   | 83.0         | 0.047             | 0.873        | 1497          | 371  |
| E2          | loftr   | sauvola / similarity          | 10    | 90.0         | 0.342             | 0.288        | 385           | 3238 |
| E2          | orb     | sauvola+chiusura / similarity | 10    | 90.0         | 0.284             | 0.049        | 743           | 87   |
| E2          | sift    | sauvola / affine              | 10    | 40.0         | 0.861             | 0.07         | 146           | 362  |

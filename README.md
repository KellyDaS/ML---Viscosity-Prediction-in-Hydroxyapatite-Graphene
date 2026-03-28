Data-Driven Viscosity Prediction in Hydroxyapatite/Graphene Inks for Additive Manufacturing: A Comparative Study of Machine Learning Models

Andreza Menezes Limaa*, Kelly Cristine da Silveira, Jayron Pereira de Andrade, Americo Cunha Jr, Alexandre Antunes Ribeiro, Antônio J. Silva Neto

Rio de Janeiro State University, Polytechnic Institute, Rua Bonfim, n° 25, 28625-570, Nova Friburgo, RJ, Brazil.
Rio de Janeiro State University, Institute of Mathematics and Statistics, Rua São Francisco Xavier, 524, 20550-900, Rio de Janeiro, RJ, Brazil.
National Institute of Technology, Avenida Venezuela, n° 82, Room 602, 20081-312, Rio de Janeiro, RJ, Brazil.
National Laboratory for Scientific Computing, Avenida Getúlio Vargas, n° 333, 25651-075, Petrópolis, RJ, Brazil.
*andrezamenezeslima@gmail.com

Abstract

Precise control of ink viscosity is a key bottleneck in printing high-quality, biocompatible hydroxyapatite/reduced-graphene-oxide (Hap/rGO) scaffolds. 
In this study, laboratory rheometry comprising 294 data points from 14 ink formulations was combined with tree-based ensemble learning to predict viscosity 
across the shear-rate range relevant to extrusion-based printing. Five algorithms - Random Forest, XGBoost, LightGBM, CatBoost, and HistGradientBoosting - were
benchmarked under four progressively richer training strategies. Although conventional random splits yielded high predictive performance, formulation-wise validation 
provided a more realistic assessment of generalization. Under nested GroupKFold, the ST4 strategy, based on Herschel–Bulkley descriptors and Optuna optimization, 
produced the most consistent results, with mean test R² values ranging from 0.764 to 0.801 and mean test MAE values from 6.96 to 7.98 Pa·s across the five algorithms. 
Under the stricter leave-one-formulation-out protocol, ST4 remained the only strategy to preserve positive mean test R² values for all evaluated models, with CatBoost 
providing the best LOFO performance (R² = 0.765; MAE = 7.27 Pa·s). For virtual screening, 1764 hypothetical HAp/rGO formulations were generated and candidates were prioritized 
within a target printability window of 0.1–1000 Pa·s. External validation using seven newly prepared inks yielded R² values between 0.737 and 0.776 and MAE values between 3.46 and 3.88 Pa·s,
confirming the predictive utility of the ST4 model family. These results demonstrate that group-aware validation is essential for small rheological datasets and that physically 
informed ensemble models support data-driven screening of ceramic inks for biomedical additive manufacturing.

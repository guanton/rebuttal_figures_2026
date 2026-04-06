## Included Figures

* **`eb_interpolation_figure_umap.pdf`**
    WLM's performance for interpolating unseen marginals for the leave-one-out (LOO) task on the Embryoid Body (EB) dataset is visualized (in UMAP space) on each of the three unseen marginals at intermediary times t2, t3, and t4. 

* **`eb_interpolation_figure_pca.pdf`**
    WLM's performance for interpolating unseen marginals for the leave-one-out (LOO) task on the Embryoid Body (EB) dataset is visualized (in 2D PCA space) on each of the three unseen marginals at intermediary times t2, t3, and t4. 

* **`oceans_interpolation_figure.pdf`**
    WLM's performance for interpolating four unseen marginals (even-indexed times) on the Gulf of Mexico ocean vortex dataset is visualized.

* **`combined_w1_runtime.pdf`**
    Plot for the performance (W1 error on EB LOO holdout marginal) vs. runtime trade-off for mini-batching. 3 seeds were run per batch size for each of the three holdout indices. The three previous best performances are plotted as baselines.

## Included animations

* **`boids_animations`**
    In this folder, we visualize WLM's predicted Boids dynamics given its training data (first 50 frames, up until t=24.5) and also for forecasting the continuation of these dynamics (next 51 frames, up until t=50.0) in `forecast_boids_train_and_forecast.gif`. We also include WLM's predicted Boids dynamics for completely unseen populations in `boids_generalization_to_unseen_population_i.gif` for $i=1,2,3$.

* **`gf_sde_gifs`**
    In this folder, we visualize WLM's predicted gradient-flow dynamics given its training data (first 10 frames, up until t=0.09) and also for forecasting thecontinuation of these dynamics (next 11 frames, up until t=0.2) for each of the potential functions (Bohachevsky, Oakley-O'Hagan, Quadratic, Styblinski-Tang, Wavy Plateau).


  

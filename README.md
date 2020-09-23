# Fish-yield
Predicting fish yield based on different attributes

The given training dataset consists of 1500 entries with no entry having a null component.There are three independent numerical attributes: cooking_time, dump_size, and post_cook_temp and three categorical attributes: species, region, and size_range that are
considered.The dependent variable is yield, a numeric variable.

After performing an exploratory data analysis (refer to Appendix), the approach used to predict
the yield based on the given test dataset is XGBoost regression. XGBoost regression gives
predictions with the lowest Mean Absolute Error (MAE)

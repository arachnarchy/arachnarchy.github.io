If you're looking for my academic work, you can find it at my [main site](http://danielzurek.com).

## [Spider sex identification from photos, using a ConvNet]((https://arachnarchy.github.io/spider_deep_sexer_notebook.nb.html))

I wrote this with behavioral video tracking in mind, where a fast and reliable way to identify the sex of ‘blobs’ within video frames can be helpful (for instance if the tracking script confuses identities after two animals interact). This limited version works with *Habronattus pyrrithrix* at >96% accuracy with a smallish batch of training images, and could easily be further improved with a larger batch of training images, adapted to a different species, or extended to work across species. Written with Keras for R to fit most spider labs' workflows. Notebook [here](https://arachnarchy.github.io/spider_deep_sexer_notebook.nb.html).

## [UFC Oracle](https://arachnarchy.shinyapps.io/ufc_predict/)

Mixed Martial Arts (MMA) is not a very data-informed sport (unlike, say, Baseball). Other nerdy fans have done detailed descriptive analyses, or come up with nifty predictors based on small numbers of high level stats. Here, I used the R version of Keras to train a deep neural network with around 5000 past UFC matchups, comparing 20 nitty-gritty statistics per fighter I mined from various sources. These career-level stats include for example striking accuracy, takedown defense, guard passes, leg reach, etc. The model is currently ~76% accurate. It produces win likelihoods for most fighters on the UFC roster by just entering their names in this [Shiny app](https://arachnarchy.shinyapps.io/ufc_predict/).

## [Field work rental car helper](https://arachnarchy.shinyapps.io/field_cars/)

A Shiny web app to aid decision making when booking rental cars for field work. This originated when planning a long desert field work trip. We needed to decide whether to rent a car, or use a personal car under the tight budget restraints of our grant. University departments usually reimburse personal car use by mile (without itemizing gas, depreciation, etc.). Rental cars usually offer unlimited miles but are charged by the day. Thus, some trips are more suitable for a personal car, others for a rental.

I collected these calculations into a [web app](https://arachnarchy.shinyapps.io/field_cars/) to hopefully help others spend less time on tedious logistics and more time on SCIENCE!

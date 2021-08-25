# My Google Colab Projects

## TopNewFollowers_Twitter features scrapping the top growing Twitter profiles via Social Bakers website.
##### Inspiration: Netflix series Money Heist co-stars once mentioned surge in social media followers foretold the success of the show
##### Objective: To find top trending & upcoming micro celebrity profiles before mainstream public via public social media data (for free!) 
  1. Scrapping the top profiles "href"s of each supported country by going thru the web server directory
  2. Using Selenium to obtain their follower counts over the past 6 months (from a JS chart) - which is time consuming but necessary
  3. Filtering results to obtain profiles with at least 10k followers and on a steady rising trend
  4. Computing, categorizing & ranking profiles with various metric such as pct_change_followers, # of followers, country, industry
  5. Outputs top profiles under the set variables (e.g. highest pct_chg in follower count over 2 weeks)
  
## Vid2Pdf features the conversion of typical education video slideshows (with or without talking heads) to proper ppt or pdf slides.
##### Inspiration: Online video courses do not provide slides. Could not find any program/sites that provide this service.
##### Objective: To convert video slideshows to clean slides without any loss of quality (and slides!)
  1. Upload video file, if required, note the pixel dimensions of a rectangle to cover the talking head in the video
  2. Extract key frames from the video file using python's av library
  3. Combining the frames to make a more succint video
  4. Remove talking head by covering with a black rectangle (if neccessary) & repeat 2 to obtain frames again for processing
  5. Clean up any duplicate frames (with Hamming distance) and compress the frames for easier processing
  6. Outputs in both PDF and PPT formats (not perfect but good enough for simple use cases)
  7. Managed to obtain a 500 page slideshow from a 5 hr long (combined) video exam prep course in under 30 mins

## USEquityML features an attempt to create alpha generating signals from historical fundamental data.
##### Inspiration: Stock investment profit-driven project
##### Objective: To use machine learning algos to quantify trends in stocks that show a 10-100x return within a one-year period.
  1. Obtain and clean data using pandas dataframes
  2. Define ML algorithms including (Decision Tree, Random Forest, K-Nearest Neighbours, Support Vector Machines, K Means & Mean Shift)
  3. Split data for training and testing (including oversampling data to account for edge cases)
  4. Speeding up models using (1) multiprocessing and (2) concurrent futures
  5. Application of models to test data to backtest results
  6. Future improvements include using tensorflow library for GPU enhancements to work with bigger datasets

# Usage
Please note that these projects are used for educational purposes and are not intended to be used commercially. We are not liable for any damages/changes done by this project.

# License
This project is protected under the GNU licence. Please refer to the LICENSE.md for more information.

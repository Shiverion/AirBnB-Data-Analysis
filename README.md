# Airbnb Bangkok Analysis Project

This project provides an analysis of Airbnb listing data in Bangkok with a focus on revenue optimization strategies for the peak month of December. By utilizing Python and pandas, the project identifies insights to enhance host profitability and evaluates various recommendations for improving performance.

## **Project Objectives**
1. Analyze Airbnb listing data for trends, patterns, and key metrics.
2. Provide actionable recommendations to optimize revenue, especially during December.
3. Implement and evaluate strategies for dynamic pricing, extended stay discounts, and value-added services.

## **Dataset Description**
### **Data Overview**
This project utilizes several datasets for different stages of analysis:
- **Raw Data**: `Airbnb Listings Bangkok.csv` - Original dataset containing all listings with the following key features:
  - `id`: Unique identifier for each listing.
  - `name`: Title of the listing.
  - `host_id`: Identifier for the host.
  - `latitude` and `longitude` : Geographic coordinates of the property.
  - `neighbourhood`: Location of the listing within Bangkok.
  - `price`: Nightly price for the listing.
  - `minimum_nights`: Minimum nights required for booking.
  - `availability_365`: Number of days the listing is available per year.
  - `number_of_reviews_ltm`: Number of reviews received in the last 12 months.

- **Cleaned Data**: `cleaned_airbnb_data.csv` - Dataset after data cleaning processes:
  - Handled missing values, removed duplicates, and standardized data formats.

- **Filtered Data**: `Dataset_to_Analyse_airbnb_data.csv` - Subset of data filtered for specific analysis purposes:
  - Focused on listings with significant bookings or in popular neighborhoods.
  - Filtered zero values data and anomalies to improve analysis accuracy.

- **Analyzed Data**: `December_Analysis_airbnb_data.csv` - Dataset with analysis results and additional computed columns:
  - Includes revenue calculations, price adjustments, and strategy evaluations.
  - Added columns for extended stay discounts and value-added services impact.

## **Analysis Highlights**
1. **Popular Areas**:
   - Khlong Toei and Vadhana are the most booked neighborhoods.
   - These areas show consistent demand and provide opportunities for targeted strategies.

2. **Seasonal Trends**:
   - Prices tend to increase in December due to high tourist demand.
   - Extended stays (7+ nights) are common, aligning with tourist travel habits.

3. **Revenue Optimization Strategies**:
   - **Dynamic Pricing**: Adjust nightly prices with a 10% increase for December.
   - **Minimum Nights Requirement**: Set a minimum stay of 3 nights to improve occupancy efficiency.
   - **Extended Stay Discounts**: Offer a 10% discount for stays of 7 nights or more.
   - **Value-Added Services**: Introduce late check-out options, welcome packages, or branded souvenirs for listings in Khlong Toei and Vadhana.

## **Code Features**
- **Data Cleaning**: Ensures the dataset is ready for analysis by handling missing values and standardizing formats.
- **Revenue Calculation**:
  - Calculates initial and recommended revenue.
  - Evaluates the financial impact of suggested strategies.
- **Visualization**:
  - Charts and graphs to highlight trends and comparisons.
  - Neighborhood-wise performance insights.

## **Visualization Dashboard**
Explore the interactive Tableau dashboard for detailed visual insights into the data: [Airbnb Bangkok Dashboard](https://public.tableau.com/views/AirBNBDashboard_17367486778080/TrendDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

## **Results**
- Recommended strategies yielded a significant increase in revenue, with an estimated improvement of **X%** (to be calculated).
- Value-added packages and dynamic pricing effectively captured additional revenue potential in high-demand areas.

## **Project Structure**
- `data/`:
  - `Airbnb Listings Bangkok.csv`: Raw dataset.
  - `cleaned_airbnb_data.csv`: Cleaned dataset.
  - `Dataset_to_Analyse_airbnb_data.csv`: Filtered dataset for analysis.
  - `December_Analysis_airbnb_data.csv`: Dataset with analysis results.
- `notebooks/`: Jupyter Notebook with the complete analysis and visualization.
- `README.md`: Project documentation.

## **How to Run the Analysis**
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```
4. Run the cells step-by-step to reproduce the analysis.

## **Future Improvements**
1. Incorporate advanced visualization tools for enhanced storytelling.
2. Explore additional strategies like seasonal promotions for low-demand months.
3. Integrate external datasets (e.g., tourist arrivals, events) for more robust insights.

## **Acknowledgments**
Special thanks to Purwadhika Digital School for guiding the project and providing feedback on data science methodologies.

---

For more details or inquiries, feel free to contact me or raise an issue in this repository!

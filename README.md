# **Project Title**

Smart Local Food Finder – Building AI course project

## **Summary**

An AI-powered recommendation system that suggests local farmers’ markets, food trucks, or small grocery stores based on a user’s preferences, location, and dietary restrictions. Uses user behavior and reviews to improve suggestions.

## **Background**

Many people want to eat locally or support small food businesses but struggle to find relevant options nearby. This project solves:

* Difficulty discovering local food sources
* Lack of personalized recommendations for dietary preferences
* Encouraging sustainable eating habits

Personal motivation: I want to help people eat healthier, support local businesses, and reduce their carbon footprint by buying locally sourced food.

## **Data sources and AI methods**

* **Data sources:** Public APIs for locations (Google Maps, OpenStreetMap), user reviews (Yelp, TripAdvisor), and possibly CSV datasets of farmers’ markets.
* **AI methods:**

  * **Recommendation system:** Collaborative filtering using user ratings
  * **Content-based filtering:** TF-IDF or embeddings to match food categories and dietary preferences
  * **Optional geospatial filtering:** Distance-based weighting of recommendations

## **How is it used?**

Users input their location, dietary preferences (vegan, gluten-free, etc.), and optionally favorite cuisines. The system returns top recommended local food vendors or markets.

* Users: local residents or tourists looking for fresh/local food.
* Environment: mobile or web app with AI backend.

## **Challenges**

* Data sparsity: few ratings for small vendors
* Bias: recommendations may favor popular vendors
* Real-time updates: new markets or closures might not be captured
* Ethical: privacy concerns with user location data

## **What next**

* Expand to include seasonal produce recommendations
* Integrate user feedback to improve suggestions dynamically
* Add social features: friends’ recommendations and ratings

## **Acknowledgments**

* OpenStreetMap for location data
* Yelp API for reviews
* Inspired by local sustainability initiatives

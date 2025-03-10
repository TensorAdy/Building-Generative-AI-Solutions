# Personalized Real Estate Agent 

A Real Estate Application that enhances customer satisfaction by providing Personalized experience for each customer. The App improves customer engagement and makes home buying experience more fun 

## About the Project 📄

The Challenge :

Your task is to develop an innovative application named "HomeMatch". This application leverages large language models (LLMs) and vector databases to transform standard real estate listings into personalized narratives that resonate with potential buyers' unique preferences and needs.
## Implementations 🛠️

- ChromaDB
- LangChain
- OpenAI
- RAG/Augmented Response Generation
- Semantic Search

### 2. Project Structure

- HomeMatch.ipynb: This python Notebook has the Real Estate Agent Application. Additional packages need are installed 
- requirements.txt: A list of the required Python packages. This is provided by udacity in the lab environment
- listings.csv: The CSV file containing the real estate listings. These are LLM generated.

### 3. Example

The buyer's input or preferences might be something like:

```
A comfortable three-bedroom house with a spacious kitchen and a cozy living room.
A quiet neighborhood, good local schools, and convenient shopping options.
A backyard for gardening, a two-car garage, and a modern, energy-efficient heating system.
Easy access to a reliable bus line, proximity to a major highway, and bike-friendly roads.
A balance between suburban tranquility and access to urban amenities like restaurants and theaters.
```

Here's an example of how the output might look:
The sematic search will return a list of home matches follwoing the format below:

```plaintext
Neighborhood: Mountain View
Price: $700,000
Bedrooms: 3
Bathrooms: 2
House Size: 2,000 sqft
Description: Enjoy mountain living in this 3-bedroom, 2-bathroom home located in the scenic neighborhood of Mountain View. This property features a cozy living room with a wood-burning stove, a bright kitchen with mountain views, and a spacious deck for outdoor dining. The master suite offers a private balcony and a renovated bathroom with a walk-in shower. Embrace the beauty of nature in the large backyard with a garden and fruit trees.
Neighborhood Description: Mountain View offers a tranquil setting with panoramic mountain views and easy access to hiking trails and ski resorts. Residents can enjoy outdoor activities year-round, from skiing in the winter to hiking and biking in the summer. With a strong sense of community and a variety of amenities, Mountain View is the perfect place for nature lovers.
```

After augmenting the results, the matched listings will be scored and personalized using the results along the buyer's preferences and priorities. The final recommendation can look as follows:

```
Home Match Score: 90
Neighborhood: Mountain View
Price: $700,000
Bedrooms: 3
Bathrooms: 2
Size sqft: 2,000 sqft
Description: Immerse yourself in the tranquility of mountain living in this 3-bedroom, 2-bathroom home nestled in the scenic neighborhood of Mountain View.
The cozy living room with a wood-burning stove, bright kitchen with mountain views, and spacious deck for outdoor dining make this property a perfect retreat for nature lovers.
The master suite offers a private balcony and a renovated bathroom with a walk-in shower, while the large backyard with a garden and fruit trees provides ample space for gardening and relaxation.
Neighborhood Description: Mountain View offers a serene setting with panoramic mountain views and easy access to hiking trails and ski resorts.
Residents can enjoy the beauty of nature year-round, from skiing in the winter to hiking and biking in the summer. With a strong sense of community and a variety of amenities, Mountain View is an ideal choice for those seeking a peaceful and nature-filled lifestyle.
```

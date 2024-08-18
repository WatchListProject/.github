# WatchList

This application provides updated information on movies and series (media), by utilizing external APIs. Users can create personalized media lists and generate recommendations with artificial intelligence based on their personal media list.

## Architecture Diagram

![Architecture Diagram](/.github/assets/WatchList%20Backend%20Arquitecture.jpg)

*Note: The architecture of this application could have been implemented as a monolithic system. However, the decision to use a microservices architecture was made for learning purposes and to gain experience with distributed systems.*

## Key Features
- **Up-to-date Media Information**: Retrieve the latest details on movies and series through external API integrations.
- **User Media Lists**: Create and manage your personal media.
- **AI-Based Recommendations**: Get personalized media recommendations based on your list, powered by Meta's LLaMA AI model.

## Repositories

- **API Gateway**: Handles all incoming requests and routes them to the appropriate microservices. You can test the API Gateway [here](https://api-gateway-soye73t7sa-tl.a.run.app/docs) (Swagger).
- **Auth Service**: Manages user authentication and authorization.
- **Media Service**: Interacts with external APIs to fetch media data.
- **User Media Service**: Manages user media lists.
- **AI Service**: Generates media recommendations using Replicate API and LLaMA model.

## License

This project is licensed under the MIT License.

# Smart India Hackathon Workshop
# Date:19.05.2025
## Register Number:212223110044
## Name:Saranya S
## Problem Title
SIH 1555: Create a Virtual Herbal Garden that provides an interactive, educational, and immersive experience to users, showcasing the diverse range of medicinal plants used in AYUSH (Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy).
## Problem Description
Background: The AYUSH sector relies heavily on medicinal plants and herbs, which form the backbone of traditional healing practices. However, physical gardens that are not accessible to everyone. A Virtual Herbal Garden will bridge this gap by offering a digital platform where users can explore, learn, and understand the significance of various medicinal plants from the comfort of their homes. Description: Participants are tasked with developing a Virtual Herbal Garden that is engaging, informative, and user-friendly. This virtual garden should include: Interactive 3D Models: Realistic 3D models of medicinal plants that users can rotate, zoom, and explore from different angles. Detailed Information: Comprehensive details about each plant, including its botanical name, common names, habitat, medicinal uses, and methods of cultivation. Multimedia Integration: High-quality images, videos, and audio descriptions to enhance the learning experience. Search and Filter Options: Advanced search functionality to easily locate specific plants and filter them based on various criteria like medicinal uses, region, and type. Virtual Tours: Guided virtual tours highlighting specific themes, such as plants for digestive health, immunity, skin care, etc. User Interaction: Features that allow users to bookmark favourite plants, take notes, and share information on social media. Expected Outcome: The expected outcome is a comprehensive Virtual Herbal Garden that serves as a valuable educational tool for students, practitioners, and enthusiasts of the AYUSH sector. This platform should make the knowledge of medicinal plants accessible to a wider audience, promoting awareness and understanding of traditional herbal practices. It should be visually appealing, informative, and interactive, providing users with an immersive experience that combines technology with traditional knowledge.

## Problem Creater's Organization
Ministry of AYUSH, Government of India

## Idea
The proposed idea is to develop a web-based and/or mobile-compatible application that allows users to immerse themselves in a virtual garden filled with medicinal plants. Users will navigate a 3D environment, interact with plants, view informative content, and customize their learning journey. The app will combine modern web technologies with authentic AYUSH knowledge to deliver a rich educational experience.


## Proposed Solution / Architecture Diagram
# High-Level Architecture
```
               [ Frontend Interface ]
    (React.js / Vue.js + Three.js or Babylon.js)
                          |
                          V
               [ Backend Server ]
    (Node.js / Express or Django REST Framework)
                          |
                          V
                [ Database Storage ]
       (MongoDB / PostgreSQL - Plant + User Data)
                          |
       +------------------+------------------+
       |                                     |
[3D Asset CDN/Cloud Storage]       [Media Content Hosting]
(Plant Models, Textures)            (Images, Videos, Audio)
```
Optional Integrations:

Firebase for authentication and real-time data sync

ElasticSearch for efficient search/filter experience

VR compatibility for immersive headset experiences

## Use Cases
# User Role	Use Case Description
Student -	Explore herbal remedies by category, take notes for academic projects.
Healthcare - Enthusiast	Learn medicinal uses of local herbs and bookmark important ones.
Practitioner -	Use advanced filters to research plants for a specific ailment.
Tourist/Visitor -	Take a themed virtual tour on “Plants for Skin Care.”
Gardener/Home Grower -	View cultivation methods and best practices for growing herbs at home.

## Technology Stack
Component      	Technology
Frontend	      React.js / Vue.js
3D Rendering	  Three.js / Babylon.js
Backend       	Node.js / Express OR Django
Database      	MongoDB / PostgreSQL
Authentication	Firebase Auth / JWT
Cloud Storage	  AWS S3 / Firebase Storage
Search Engine  	ElasticSearch / Algolia (optional)
VR Support	    WebXR / Unity (optional)
## Dependencies
Medicinal Plant Database: Sourced from AYUSH or verified government/public botanical sources

3D Models of Plants: Custom-made or open-source 3D models in .glb/.gltf format

Media Content: Professionally recorded videos, images, and narration audio

Web Libraries/Frameworks: For UI, 3D rendering, routing, and API communication

Cloud Hosting Services: For reliable access and media delivery

Team Skills: 3D modeling, frontend/backend development, UI/UX design, content curation



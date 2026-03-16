# Carbonia
Carbonia, an iOS app submitted to the Swift Student Challenge 2026.
Carbonia is an interactive iOS learning app built for the Swift Student Challenge 2026.
It helps beginners understand the fundamentals of carbon chemistry through interactive 3D models, guided learning, and AI-powered explanations.

The goal of Carbonia is to transform abstract chemistry concepts into visual, interactive experiences so that students can explore molecular structures instead of only reading about them.

# Features

# Interactive 3D Carbon Allotropes

Explore Diamond, Graphite, Fullerene, and Amorphous Carbon in 3D

Rotate and zoom models to understand molecular geometry

 Visual Learning

Bridge the gap between 2D textbook diagrams and real 3D molecular structures

 # AI Chemistry Assistant

Powered by the Anthropic Claude API

Provides instant explanations for chemistry concepts

Context-aware responses for each section

# IUPAC Nomenclature Helper

Breaks complex naming rules into simple guided steps

#  Zero External Dependencies

Built entirely with Apple's native frameworks

# Tech Stack

SwiftUI
Used for the entire user interface including animated cards, navigation, and interactive components.

SceneKit
Used to render 3D molecular structures with native support for geometry, lighting, and camera control.

UIKit Bridge (UIViewRepresentable)
Allows SceneKit's SCNView to work inside SwiftUI.

Anthropic Claude API
Powers the AI chemistry assistant for instant student support.

# Interactions

Users can interact with molecular models using:

Pan gesture → rotate molecules

Pinch gesture → zoom in/out

Dynamic camera controls for exploring structures

These gestures were implemented using custom UIKit gesture recognizers.

# Built For

Swift Playgrounds

Swift Student Challenge 2026

The app is optimized for a Playgrounds environment, ensuring smooth performance without external package dependencies.

# What I Learned

While building Carbonia, I learned:

Integrating 3D graphics in iOS using SceneKit

Bridging UIKit components inside SwiftUI

Making real API calls using async/await

Designing educational AI prompts

Building interactive learning experiences.

# Inspiration

When I first studied carbon chemistry in Class 9, the topic felt overwhelming. Concepts like allotropes, bonding structures, and IUPAC naming required multiple readings to understand.

Carbonia was built to solve that problem — turning confusing textbook concepts into interactive visual experiences where students can explore and ask questions freely.

# Future Improvements

More organic chemistry topics

Additional molecules and reactions

Offline AI explanations

Interactive quizzes and exercises

# im1ai.ca Demo Version - Operation Guide

## Overview

im1ai.ca is a modular, AI-native platform where users can create and interact with personal AI spaces. This guide covers the key features, functionality, and navigation for each of the four main components: Entrance Page, VisitRoom, StudyRoom, and ThoughtLens.

## 1. Entrance Page - The Gateway

### Key Points
- **Visual Interface**: Space-themed background with stars representing users
- **Navigation Hub**: Central point to access all other platform components
- **Public Exploration**: Allows visitors to explore available AI worlds

### Button Functions
- **HUD Panel**: Displays system information and available AI worlds
- **Control Panel**: Contains search functionality and navigation options
- **Star Icons**: Represent different types of users:
  - Permanent users (P)
  - Temporary users (T)
  - Sponsor users

### Relationships
- **Gateway to Platform**: Entry point to all other components
- **World Discovery**: Allows users to find and visit other users' AI worlds
- **ThoughtLens Access**: Contains a special star that links to the ThoughtLens module

## 2. VisitRoom - Personal AI Showcase

### Key Points
- **Two Operating Modes**:
  - **Visiting Mode**: Public-facing view for visitors
  - **Editing Mode**: For signed-in users to customize their space
- **Trust Ratio System**: Visual indicator of AI personalization level
- **Personal AI Chat**: Interaction with the user's trained AI personality

### Button Functions
- **Chat Interface**: Send messages to the personal AI
- **Public Library Panel**: Browse books, films, and documents shared by the user
- **Trust Ratio Display**: Shows how personalized the AI really is
- **Edit Mode Toggle**: Switches between visiting and editing modes (for owners)
- **Go To StudyRoom Button**: Direct navigation to the StudyRoom (for owners)
- **Background Editor**: Create/edit visual background (in Edit Mode)
- **Content Library Manager**: Control visibility of personal content (in Edit Mode)

### Relationships
- **Connected to StudyRoom**: Uses training data created in StudyRoom
- **Personalized by Owner**: Reflects the personality and content shared by the world owner
- **Public-Facing**: Main interface for visitors to interact with a user's personal AI

## 3. StudyRoom - AI Training Space

### Key Points
- **Training Interface**: Upload and manage training data for personal AI
- **Conversation Data**: Create and store Q&A pairs for AI training
- **File Management**: Upload and organize personal documents

### Button Functions
- **Upload Training Data**: Upload JSONL files for fine-tuning
- **Create Fine-Tune**: Submit uploaded data to create a fine-tuned model
- **Save Diary**: Record personal notes and thoughts
- **File Upload**: Upload documents (PDFs, text files, etc.)
- **Chat Completions**: Test AI responses with the OpenAI API
- **Save to JSONL**: Save conversations as training data in JSONL format

### Relationships
- **Feeds VisitRoom**: Training data created here powers the personal AI in VisitRoom
- **Personal Workspace**: Private space for users to develop their AI personality
- **Data Repository**: Stores uploaded files and conversation data

## 4. ThoughtLens - Cognitive Reflection Zone

### Key Points
- **Focal Points**: Current topics and news items to analyze
- **Multiple Lenses**: View topics through different cognitive frameworks
- **AI-Generated Questions**: Thought-provoking questions based on selected lens
- **Marketplace**: Access to premium lens collections

### Button Functions
- **Lens Selector**: Choose different cognitive perspectives (economic, political, ethical, historical)
- **Focal Point Browser**: Browse and select topics to analyze
- **Question Generator**: Generate thought-provoking questions based on the selected lens and topic
- **Marketplace Access**: Browse and purchase premium lens collections

### Relationships
- **Accessible from Entrance**: Special star in the Entrance page links to ThoughtLens
- **Complementary to Personal AI**: Provides cognitive frameworks that can inform personal AI training
- **Standalone Module**: Can be used independently of other platform components

## Navigation Between Components

1. **Entrance Page → VisitRoom**:
   - Click on a user star to visit their personal AI world

2. **VisitRoom → StudyRoom**:
   - Click "Go To StudyRoom" button (only available to world owners)

3. **StudyRoom → VisitRoom**:
   - After training data is saved, return to VisitRoom to see the updated AI

4. **Entrance Page → ThoughtLens**:
   - Click on the ThoughtLens star in the star map

5. **Any Component → Entrance Page**:
   - Use navigation controls typically found in the interface header

## Technical Integration

All components are integrated through shared libraries:
- **auth-lib**: Handles authentication across all components
- **config-lib**: Provides shared configurations
- **access-control-lib**: Manages access logic for rooms
- **navigation-lib**: Handles navigation between components
- **data-access-lib**: Provides data services for Firebase integration
- **data-models**: Defines shared data schemas

This modular architecture allows for consistent user experience while maintaining separation of concerns between different functional areas of the platform.

Here is the `verbal_identity.md` file, which provides detailed guidelines on how to implement and understand the "Verbal Identity" section of the Brand Guidelines Schema (BGS). This document will help users define the brand’s tone of voice, messaging frameworks, vocabulary preferences, and boilerplate content.

### **verbal_identity.md**

```markdown
# Verbal Identity

The **Verbal Identity** section of the Brand Guidelines Schema (BGS) defines how a brand communicates through language, ensuring consistency, clarity, and authenticity across all touchpoints. It includes guidelines for tone of voice, messaging frameworks, vocabulary, and standardized boilerplate content.

## Table of Contents
1. [Tone of Voice](#tone-of-voice)
2. [Messaging Framework](#messaging-framework)
3. [Vocabulary Guidelines](#vocabulary-guidelines)
4. [Boilerplates](#boilerplates)

---

## 1. Tone of Voice

### Overview
The **tone of voice** represents the personality and emotion infused into a brand's communications. It reflects how the brand "speaks" to its audience and ensures that all content is consistent, whether it’s a tweet, a blog post, or an email.

### Fields
- **description**: A brief explanation of the brand's overall tone of voice. For example, "Friendly, informative, and encouraging."
- **attributes**: Key adjectives that describe the tone, such as "Warm," "Professional," or "Innovative."
- **do_s**: A list of practices to follow to maintain the desired tone. For example, "Use inclusive language," or "Speak in an active voice."
- **dont_s**: A list of practices to avoid to ensure the tone stays consistent. For example, "Avoid using technical jargon," or "Don't use overly formal language."

### Example
```json
"tone_of_voice": {
  "description": "Friendly and informative.",
  "attributes": ["Warm", "Knowledgeable", "Motivating"],
  "do_s": ["Use positive language", "Be encouraging"],
  "dont_s": ["Avoid negativity", "Don’t use complex terminology"]
}
```

---

## 2. Messaging Framework

### Overview
The **Messaging Framework** provides guidance on key messages, value propositions, and storytelling techniques that define how the brand communicates its core messages. It ensures that all content is aligned with the brand's objectives and resonates with its audience.

### Fields
- **key_messages**: Contains the core brand messages, including:
  - **brand_promise**: A statement of what the brand commits to delivering.
  - **value_propositions**: The unique benefits and advantages offered by the brand.
  - **key_features**: The main features or attributes of the brand's products or services.
- **elevator_pitch**: A concise summary of the brand's offering, designed to quickly inform and engage someone in a short amount of time.
- **sample_messages**: Pre-written examples of on-brand messaging for different contexts, such as:
  - **social_media**: Messaging suitable for platforms like Twitter, Facebook, or Instagram.
  - **email**: Example text for newsletters or promotional emails.
  - **ad_copy**: Messaging used in advertisements.
  - **website**: Phrases or statements used on the brand's website.

### Example
```json
"messaging_framework": {
  "key_messages": {
    "brand_promise": "To provide eco-friendly products that make sustainable living simple.",
    "value_propositions": ["High-quality products", "Eco-friendly materials"],
    "key_features": ["Reusable", "Biodegradable"]
  },
  "elevator_pitch": "EcoFriendly Co. offers sustainable products that make it easy to lead a greener lifestyle.",
  "sample_messages": {
    "social_media": "Choosing eco-friendly products is a small change that makes a big impact. #SustainableLiving",
    "email": "Discover products that help you lead a greener, more sustainable lifestyle.",
    "ad_copy": "Switch to sustainable solutions with EcoFriendly Co. – because every small change counts!",
    "website": "Our mission is to make sustainable living easy and accessible for everyone."
  }
}
```

---

## 3. Vocabulary Guidelines

### Overview
The **Vocabulary Guidelines** section defines the preferred and avoided words, ensuring that the language used across all brand communications is consistent with the brand's identity.

### Fields
- **preferred_words**: Words or phrases that should be used frequently in brand messaging to reinforce the brand identity (e.g., "Sustainable," "Eco-friendly").
- **words_to_avoid**: Words or phrases that should be avoided to maintain the brand's tone and messaging consistency (e.g., "Cheap," "Plastic").
- **grammar_and_style**: Guidelines for maintaining consistency in grammar, punctuation, and overall writing style. This might include rules for capitalization, sentence structure, or tone preferences.

### Example
```json
"vocabulary_guidelines": {
  "preferred_words": ["Sustainable", "Eco-friendly", "Reusable"],
  "words_to_avoid": ["Plastic", "Wasteful"],
  "grammar_and_style": "Use active voice, avoid overly technical terms, and maintain a friendly tone."
}
```

---

## 4. Boilerplates

### Overview
The **Boilerplates** section contains pre-written, standardized content that can be used across various brand communication materials. This ensures that consistent and accurate brand information is available for different contexts.

### Boilerplate Types
- **short_description**: A concise description of the brand, suitable for social media bios or quick introductions.
- **long_description**: A detailed description for the "About Us" section on the website or in presentations.
- **press_release_boilerplate**: A standard paragraph used at the end of press releases.
- **product_or_service_description**: A description of the brand's products or services, used in catalogs or brochures.
- **about_us_statement**: A paragraph that captures the essence of the brand, used on the company’s website or in media kits.
- **media_kit_description**: A description specifically formatted for use in media kits.
- **new_article**: A structured format for news articles, including fields like title, introduction, body, conclusion, and call to action.

### Example
```json
"boilerplates": {
  "short_description": "EcoFriendly Co. offers sustainable products for everyday living.",
  "long_description": "EcoFriendly Co. is a leader in sustainable products, offering a range of eco-friendly solutions that inspire individuals and businesses to adopt greener lifestyles.",
  "press_release_boilerplate": "EcoFriendly Co. is dedicated to making sustainability accessible. For more information, visit www.ecofriendlyco.com.",
  "product_or_service_description": "Our range includes reusable bags, biodegradable packaging, and eco-friendly household items.",
  "about_us_statement": "At EcoFriendly Co., we believe in the power of small changes to make a big impact.",
  "media_kit_description": "EcoFriendly Co. is a brand committed to providing eco-friendly products that inspire sustainable living.",
  "new_article": {
    "title": "EcoFriendly Co. Launches New Line of Biodegradable Packaging",
    "introduction": "EcoFriendly Co. is excited to announce the launch of our new biodegradable packaging solutions.",
    "body": [
      "These products offer an environmentally friendly alternative to traditional packaging.",
      "CEO Jane Doe stated, 'Our new packaging line is an example of our commitment to sustainability.'"
    ],
    "conclusion": "Visit our website to learn more about our biodegradable packaging solutions.",
    "call_to_action": "Explore our full range of eco-friendly products today."
  }
}
```

---

By following the guidelines in this **Verbal Identity** section, brands can ensure that their communication remains consistent, authentic, and aligned with their overall identity. This helps build a recognizable voice that resonates with the target audience and reinforces the brand's values and mission.
```

### Key Features of `verbal_identity.md`:
- **Clear Structure**: The document is organized into sections for each component of the Verbal Identity, making it easy to navigate.
- **Detailed Explanations**: Each part of the Verbal Identity section is explained in detail, helping users understand how to apply the schema effectively.
- **JSON Examples**: Practical examples are provided for each section, giving users a clear idea of how to implement the schema in their brand guidelines.

You can include this file in your documentation to provide comprehensive guidance on implementing the Verbal Identity section of the Brand Guidelines Schema.
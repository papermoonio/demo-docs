---
title: Quick Start
description: Your express lane to jumpstart your journey, offering concise and simplified steps to set up and get your hands on, ensuring you can begin exploring and building without any unnecessary delays.
---

# Quick Start

## Introduction

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Prerequisites

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

```bash
npm i lorem-ipsum
```

## Get Started

Lorem Ipsum is simply dummy text of the printing and typesetting industry:

1. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book
2. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged
3. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

=== "JavaScript"

    ```js
    // Lorem ipsum variable to store text
    const loremIpsum = "Lorem ipsum dolor sit amet, consectetur adipiscing elit.";
    const count = 52036;

    // Function to manipulate Lorem Ipsum text
    function manipulateLoremIpsum(text, count) {
      // Split the text into an array of words
      const words = text.split(' ');

      // Reverse the order of words
      const reversedText = words.reverse().join(' ');

      count += 1;
      return reversedText;
    }

    // Call the function and display the result
    const reversedText = manipulateLoremIpsum(loremIpsum, count);
    console.log(reversedText);
    console.log(`Current count is: `${count});
    ```

=== "Python"

    ```py
    # Lorem ipsum variable to store text
    lorem_ipsum = "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
    count = 52036

    # Function to manipulate Lorem Ipsum text
    def manipulate_lorem_ipsum(text):
        # Split the text into a list of words
        words = text.split(' ')

        # Reverse the order of words
        reversed_text = ' '.join(reversed(words))

        count += 1
        return reversed_text

    # Call the function and display the result
    reversed_text = manipulate_lorem_ipsum(lorem_ipsum)
    print(reversed_text)
    print(f"Current count is: {count}")
    ```

!!! note
    Lorem Ipsum is **simply dummy text** of the printing and typesetting industry.

## Account Setup

Lorem Ipsum is simply dummy text of the printing and typesetting industry:



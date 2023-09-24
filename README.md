# take-a-note
Transcribe on-screen text with a button-press

This project will use Python to allow the user to transcribe any on-screen text (such as subtitles in a video game) to a designated text file with a key command while running.

The first iteration will transcribe whenever the program is run from the command line by taking a screenshot, using OCR to read the text from the image, printing the text to a file, then deleting the screenshot.

The next iteration will package it into an executable and allow the main functionality to be triggered with a keypress while running.

Concept based on the Universal Pause - a platform-agnostic user convenience utility. Future plans would be to toggle auto-transcription on and off, so a continuous file could be created. The main use-case in mind is to allow video game dialogue subtitles or text boxes to be automatically transcribed in games that lack a basic conversation log such as Elden Ring, or have insufficient summaries in their quest tracking systems. This could apply to many other contexts for both convenience and accessibility, or even language learning or translation applications.

Audio transcription is another possible approach to this, but more prone to error. An associated project using that approach may be considered later.

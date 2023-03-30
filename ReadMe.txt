// Initialize counters
sentence_length = 0
word_count = 0
vowel_count = 0

// Read in sentence
sentence = input("Enter a sentence ends with . : ")
if (sentence.length + 1 <> ".")
sentence = input("Enter a sentence ends with . : ")
// Traverse through each character in the sentence
for character in sentence:
    // Increment sentence length counter
    sentence_length = sentence_length + 1
    
    // Increment word count counter if character is a space
    if character == " ":
        word_count = word_count + 1
        
    // Increment vowel count counter if character is a vowel
    if character in "aeiouAEIOU":
        vowel_count = vowel_count + 1

// Add 1 to word count for the last word in the sentence
word_count = word_count + 1

// Print out counters
print("Sentence length:", sentence_length)
print("Number of words:", word_count)
print("Number of vowels:", vowel_count)
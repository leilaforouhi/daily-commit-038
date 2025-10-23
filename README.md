def count_words(text):
    words = text.spliT()
    return len(words)

if __name__ == "__main__":
    sample = "GitHub daily commits keep me consistent"
    print(f"Word count: {count_words(sample)}")

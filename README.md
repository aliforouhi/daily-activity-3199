# daily_update.p
import datetime
import random

print("Daily GitHub activity - Day 31")

today = datetime.date.today()

# Generate random words and count total characters
words = ["python", "github", "activity", "random", "update", "script", "daily"]
selected_words = random.sample(words, 4)

total_chars = sum(len(w) for w in selected_words)

print(f"Today's date: {today}")
print(f"Selected words: {selected_words}")
print(f"Total character count: {total_chars}")
print(f"Longest word: {max(selected_words, key=len)}")

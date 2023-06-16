def count_favourite_singers(songs, singers):
    singer_counts = {}
    max_count = 0

    for i in range(songs):
        singer = singers[i]
        if singer in singer_counts:
            singer_counts[singer] += 1
        else:
            singer_counts[singer] = 1

        max_count = max(max_count, singer_counts[singer])

    favourite_singers = 0
    for count in singer_counts.values():
        if count == max_count:
            favourite_singers += 1

    return favourite_singers

# Read input
songs = int(input())
singers = list(map(int, input().split()))

# Count favourite singers
result = count_favourite_singers(songs, singers)

# Print the result
print(result)

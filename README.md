# Recently Played Songs Store

This is an in-memory store for recently played songs based on users. It stores a list of song-user pairs, and when the store reaches its capacity, the least recently played song is evicted.

## Project Structure

- `Song.java`: Model class representing the song and user.
- `RecentlyPlayedStore.java`: Core logic for managing the recently played songs.
- `RecentlyPlayedStoreTest.java`: Test cases written using TestNG.

## How to Run

### Prerequisites

- Java 8 or higher
- Maven

### Steps to Execute

1. Clone the repository:
   ```bash
   git clone <repo_url>

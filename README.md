# Flower Scan Model

### About
Model was created using MobileNetV2 and then build API using Flask.

## Endpoints

### `GET /`

Response succes!

**Response:**

- `200 OK` on success

---

### `POST /Upload`

Classify Image of the Flowers

**Parameters:**

- `file`: The image file of the flowers to classify.

**Response:**

- `200 OK` on success

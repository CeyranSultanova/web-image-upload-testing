# Image Upload – API Checklist

| Check | ID | Priority | Checklist Item |
|---|---|---|---|
| ☐ | API-001 | Critical | Validate that a valid JPEG image smaller than 10 MB can be uploaded successfully through the API. |
| ☐ | API-002 | High | Validate that a successful upload returns the expected HTTP status code. |
| ☐ | API-003 | High | Validate that the successful upload response contains the expected image data/reference. |
| ☐ | API-004 | Critical | Validate that the uploaded image is associated with the correct entity/customer. |
| ☐ | API-005 | Critical | Validate that an image just below 10 MB is accepted. |
| ☐ | API-006 | Critical | Validate that an image of exactly 10 MB is rejected. |
| ☐ | API-007 | Critical | Validate that an image larger than 10 MB is rejected. |
| ☐ | API-008 | High | Validate that the expected error status and message are returned for an oversized image. |
| ☐ | API-009 | Critical | Validate that unsupported file formats are rejected by the API. |
| ☐ | API-010 | High | Validate that the expected error status and message are returned for unsupported formats. |
| ☐ | API-011 | Critical | Validate that changing an unsupported file extension to .jpeg does not bypass MIME/content validation. |
| ☐ | API-012 | High | Validate that a corrupted JPEG file is rejected. |
| ☐ | API-013 | High | Validate that an empty/0-byte image file is rejected. |
| ☐ | API-014 | Critical | Validate that the entity save request succeeds when the image field is not provided. |
| ☐ | API-015 | Critical | Validate that the entity can be successfully created/saved without an image. |
| ☐ | API-016 | High | Validate that retrieving an entity without an image returns the expected null/empty image value without an error. |
| ☐ | API-017 | Critical | Validate that only one image can be associated with an entity. |
| ☐ | API-018 | High | Validate API behavior when attempting to upload a second image without replacing the first one. |
| ☐ | API-019 | Critical | Validate that an existing image can be successfully replaced through the API. |
| ☐ | API-020 | High | Validate that replacing an image returns the new image data/reference. |
| ☐ | API-021 | High | Validate that the old image reference is no longer associated with the entity after replacement. |
| ☐ | API-022 | Critical | Validate that an existing image can be successfully deleted through the API. |
| ☐ | API-023 | High | Validate that the deleted image is no longer returned when the entity is retrieved. |
| ☐ | API-024 | Medium | Validate API behavior when attempting to delete an image that does not exist. |
| ☐ | API-025 | Critical | Validate that unauthorized users cannot upload an image for a protected entity. |
| ☐ | API-026 | Critical | Validate that unauthorized users cannot replace an existing image. |
| ☐ | API-027 | Critical | Validate that unauthorized users cannot delete an existing image. |
| ☐ | API-028 | Critical | Validate that one user cannot modify or delete another user's image. |
| ☐ | API-029 | High | Validate that failed upload requests do not create an image association. |
| ☐ | API-030 | High | Validate that repeated/duplicate upload requests do not create multiple image associations. |

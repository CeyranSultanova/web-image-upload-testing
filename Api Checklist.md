| ID      | Priority | API Test Case                                                                                                                     |
| ------- | -------- | --------------------------------------------------------------------------------------------------------------------------------- |
| API-001 | High     | **Validate** successful JPEG image upload when the file size is less than 10 MB.                                                  |
| API-002 | High     | **Validate** that the API returns the expected success status code and response after a valid image upload.                       |
| API-003 | High     | **Validate** that the uploaded image is correctly associated with the corresponding entity/user in the backend.                   |
| API-004 | High     | **Validate** that the API rejects an image with a file size of exactly 10 MB.                                                     |
| API-005 | High     | **Validate** that the API rejects an image larger than 10 MB.                                                                     |
| API-006 | High     | **Validate** successful upload of a JPEG image with a file size just below 10 MB.                                                 |
| API-007 | High     | **Validate** that the API rejects unsupported file formats such as PNG, GIF, WEBP, PDF, SVG, BMP, and TIFF.                       |
| API-008 | High     | **Validate** that changing an unsupported file extension to `.jpeg` does not bypass backend file-type validation.                 |
| API-009 | High     | **Validate** that a corrupted JPEG file is rejected by the API.                                                                   |
| API-010 | High     | **Validate** that only one image can be associated with the entity at a time.                                                     |
| API-011 | High     | **Validate** API behavior when attempting to upload a second image while an image already exists.                                 |
| API-012 | High     | **Validate** successful replacement/editing of an existing image with another valid JPEG image.                                   |
| API-013 | High     | **Validate** that the previous image is no longer associated with the entity after successful replacement.                        |
| API-014 | High     | **Validate** successful deletion of an existing image.                                                                            |
| API-015 | High     | **Validate** that the deleted image is no longer returned by the API after deletion.                                              |
| API-016 | High     | **Validate** API behavior when attempting to delete an image that does not exist.                                                 |
| API-017 | High     | **Validate** that creating/saving the entity without an image is successful.                                                      |
| API-018 | High     | **Validate** that retrieving an entity without an image returns the expected empty/null image value.                              |
| API-019 | High     | **Validate** that retrieving an entity with an uploaded image returns the correct image information.                              |
| API-020 | High     | **Validate** that the backend provides the correct image state/data required for displaying the image icon when an image exists.  |
| API-021 | High     | **Validate** that the backend provides the correct image state/data when no image exists so that the image icon is not displayed. |
| API-022 | High     | **Validate** that an unauthorized user cannot upload an image.                                                                    |
| API-023 | High     | **Validate** that an unauthorized user cannot edit/replace an existing image.                                                     |
| API-024 | High     | **Validate** that an unauthorized user cannot delete an existing image.                                                           |
| API-025 | High     | **Validate** that a user cannot edit or delete an image belonging to another user/entity.                                         |
| API-026 | High     | **Validate** that the API returns the expected error status code and error message for invalid file size.                         |
| API-027 | High     | **Validate** that the API returns the expected error status code and error message for an invalid file format.                    |
| API-028 | Medium   | **Validate** API behavior when the image parameter is missing from the upload request.                                            |
| API-029 | Medium   | **Validate** API behavior when an empty file is sent as the image.                                                                |
| API-030 | Medium   | **Validate** that repeated identical upload requests do not result in multiple images being associated with the entity.           |

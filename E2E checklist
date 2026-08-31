| ID      | Priority | E2E Checklist                                                                                                                              |
| ------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| E2E-001 | High     | **Validate** that the user can upload a valid JPEG image smaller than 10 MB and successfully save the entity.                              |
| E2E-002 | High     | **Validate** that the uploaded image is successfully processed by the API and saved in the database/storage.                               |
| E2E-003 | High     | **Validate** that the correct image reference/ID is associated with the correct entity in the database after saving.                       |
| E2E-004 | High     | **Validate** that the saved image can be successfully retrieved from the backend after reopening the entity.                               |
| E2E-005 | High     | **Validate** that the image retrieved from the backend/database is correctly displayed on the UI after reopening the entity.               |
| E2E-006 | High     | **Validate** that the image icon appears on the page after an image is successfully uploaded and saved.                                    |
| E2E-007 | High     | **Validate** that the user can complete and save the entire flow without uploading an image.                                               |
| E2E-008 | High     | **Validate** that saving the entity without an image does not cause API or backend validation errors.                                      |
| E2E-009 | High     | **Validate** that saving the entity without an image does not create an invalid image record/reference in the database.                    |
| E2E-010 | High     | **Validate** that no image is displayed after reopening an entity that was saved without an image.                                         |
| E2E-011 | High     | **Validate** that the image icon is not displayed when the entity does not have an image.                                                  |
| E2E-012 | High     | **Validate** that only one image can be associated with an entity throughout the complete flow.                                            |
| E2E-013 | High     | **Validate** that attempting to add a second image does not result in multiple image records/references being associated with the entity.  |
| E2E-014 | High     | **Validate** that the user can replace an existing image with another valid JPEG image and successfully save the changes.                  |
| E2E-015 | High     | **Validate** that replacing an image updates the corresponding image data/reference in the database/storage.                               |
| E2E-016 | High     | **Validate** that the previous image/reference is no longer associated with the entity after successful replacement.                       |
| E2E-017 | High     | **Validate** that only the newly replaced image is returned by the API and displayed on the UI after reopening the entity.                 |
| E2E-018 | High     | **Validate** that the image icon remains correctly displayed after an existing image is replaced.                                          |
| E2E-019 | High     | **Validate** that the user can successfully delete a previously saved image.                                                               |
| E2E-020 | High     | **Validate** that deleting the image correctly removes or updates its reference in the database.                                           |
| E2E-021 | High     | **Validate** that the deleted image is no longer returned by the API.                                                                      |
| E2E-022 | High     | **Validate** that the deleted image is no longer displayed after refreshing or reopening the entity.                                       |
| E2E-023 | High     | **Validate** that the image icon disappears after the saved image is deleted.                                                              |
| E2E-024 | High     | **Validate** that the entity continues to work correctly and can be saved after its image is deleted.                                      |
| E2E-025 | High     | **Validate** that a valid JPEG image with a size just below 10 MB can be uploaded, saved, stored, retrieved, and displayed successfully.   |
| E2E-026 | High     | **Validate** that a JPEG image of exactly 10 MB is rejected and is not stored in the database/storage.                                     |
| E2E-027 | High     | **Validate** that a JPEG image larger than 10 MB is rejected and is not stored in the database/storage.                                    |
| E2E-028 | High     | **Validate** that the entity can still be successfully saved without an image after an oversized image is rejected.                        |
| E2E-029 | High     | **Validate** that unsupported file formats such as PNG, GIF, WEBP, PDF, SVG, BMP, and TIFF are rejected and are not stored.                |
| E2E-030 | High     | **Validate** that renaming an unsupported file to `.jpeg` does not bypass file-type validation or result in the file being stored.         |
| E2E-031 | High     | **Validate** that a corrupted or invalid JPEG image is rejected and is not stored in the database/storage.                                 |
| E2E-032 | High     | **Validate** that rejection of an invalid image does not prevent the user from continuing and saving the entity without an image.          |
| E2E-033 | High     | **Validate** that the image information returned by the API corresponds to the image reference associated with the entity in the database. |
| E2E-034 | High     | **Validate** that the uploaded image remains correctly associated with the entity after page refresh.                                      |
| E2E-035 | High     | **Validate** that the uploaded image remains correctly associated with the entity after logout and login.                                  |
| E2E-036 | High     | **Validate** that an image uploaded for one entity is not displayed or associated with another entity.                                     |
| E2E-037 | High     | **Validate** that a user cannot modify or delete an image belonging to an entity they are not authorized to modify.                        |
| E2E-038 | High     | **Validate** that an upload or save failure does not create an image record/reference in the database.                                     |
| E2E-039 | High     | **Validate** that an upload or save failure does not cause the UI to display the image or image icon as successfully saved.                |
| E2E-040 | Medium   | **Validate** that cancelling image selection does not upload, save, or create an image reference.                                          |
| E2E-041 | Medium   | **Validate** that cancelling image replacement keeps the previously saved image unchanged in the UI, backend, and database.                |
| E2E-042 | Medium   | **Validate** that repeated upload/save actions do not create duplicate image records or duplicate associations.                            |
| E2E-043 | Medium   | **Validate** that a valid JPEG image with a long filename can complete the full upload and save flow successfully.                         |
| E2E-044 | Medium   | **Validate** that a valid JPEG filename containing spaces or supported special characters does not break the complete flow.                |
| E2E-045 | Medium   | **Validate** that the complete image upload, save, edit, delete, and no-image flows work correctly across supported browsers.              |

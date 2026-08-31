# Image Upload – E2E Checklist

| Check | ID | Priority | Checklist Item |
|---|---|---|---|
| ☐ | E2E-001 | Critical | Validate the complete flow: upload a valid JPEG smaller than 10 MB → save → reopen the entity → verify that the image is displayed. |
| ☐ | E2E-002 | Critical | Validate that the uploaded image is processed by the API and saved in the database/storage. |
| ☐ | E2E-003 | Critical | Validate that the correct image reference/ID is associated with the correct entity in the database. |
| ☐ | E2E-004 | High | Validate that the saved image is successfully retrieved from the backend after reopening the entity. |
| ☐ | E2E-005 | Critical | Validate that the image retrieved from backend/storage is correctly displayed on the UI. |
| ☐ | E2E-006 | High | Validate that the image icon appears after a valid image is successfully saved. |
| ☐ | E2E-007 | Critical | Validate the complete save flow without uploading an image. |
| ☐ | E2E-008 | Critical | Validate that saving without an image does not produce an API/backend validation error. |
| ☐ | E2E-009 | High | Validate that saving without an image does not create an invalid image record/reference in the database. |
| ☐ | E2E-010 | High | Validate that no image or image icon is displayed after reopening an entity saved without an image. |
| ☐ | E2E-011 | Critical | Validate that only one image remains associated with the entity throughout the complete flow. |
| ☐ | E2E-012 | Critical | Validate the complete image replacement flow: existing image → replace → save → reopen → new image displayed. |
| ☐ | E2E-013 | Critical | Validate that replacing the image updates the image reference/data in database/storage. |
| ☐ | E2E-014 | High | Validate that the old image is no longer associated with the entity after successful replacement. |
| ☐ | E2E-015 | Critical | Validate the complete deletion flow: delete image → save → refresh/reopen → image remains deleted. |
| ☐ | E2E-016 | Critical | Validate that deleting an image removes or correctly updates its database reference. |
| ☐ | E2E-017 | High | Validate that the deleted image is no longer returned by the API. |
| ☐ | E2E-018 | High | Validate that the image icon disappears after image deletion. |
| ☐ | E2E-019 | Critical | Validate that the entity remains usable and can be saved after deleting the image. |
| ☐ | E2E-020 | Critical | Validate that an image just below 10 MB completes the full upload → save → storage → retrieve → display flow successfully. |
| ☐ | E2E-021 | Critical | Validate that an image of exactly 10 MB is rejected and is not saved in database/storage. |
| ☐ | E2E-022 | Critical | Validate that an image larger than 10 MB is rejected and is not saved in database/storage. |
| ☐ | E2E-023 | High | Validate that the entity can still be saved without an image after an oversized image is rejected. |
| ☐ | E2E-024 | Critical | Validate that unsupported file formats are rejected and are not stored. |
| ☐ | E2E-025 | Critical | Validate that renaming an unsupported file to .jpeg does not bypass validation and the file is not stored. |
| ☐ | E2E-026 | High | Validate that a corrupted JPEG is rejected and not stored. |
| ☐ | E2E-027 | High | Validate that rejection of an invalid image does not prevent the user from saving the entity without an image. |
| ☐ | E2E-028 | Critical | Validate that API-returned image data/reference corresponds to the image reference stored in the database. |
| ☐ | E2E-029 | High | Validate that the saved image remains associated with the entity after page refresh. |
| ☐ | E2E-030 | High | Validate that the saved image remains correctly associated after logout and login. |
| ☐ | E2E-031 | Critical | Validate that an image belonging to one entity is not displayed for another entity. |
| ☐ | E2E-032 | Critical | Validate that one user cannot edit or delete another user's image. |
| ☐ | E2E-033 | Critical | Validate that an upload/save failure does not create an image record/reference in the database. |
| ☐ | E2E-034 | High | Validate that an upload/save failure does not cause the UI to show the image as successfully saved. |
| ☐ | E2E-035 | Medium | Validate that cancelling image selection does not create an image record or change the saved state. |
| ☐ | E2E-036 | High | Validate that cancelling image replacement keeps the previous image unchanged in UI, API, and database/storage. |
| ☐ | E2E-037 | High | Validate that repeated upload/save actions do not create duplicate image records or associations. |
| ☐ | E2E-038 | Medium | Validate the complete image upload, replace, delete, and no-image flows across supported browsers. |

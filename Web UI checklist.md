# Image Upload – Functional & UI Checklist

| Check | ID | Priority | Checklist Item |
|---|---|---|---|
| ☐ | UI-001 | High | Validate that the user can upload a valid JPEG image smaller than 10 MB. |
| ☐ | UI-002 | High | Validate that the uploaded image is displayed correctly after selection. |
| ☐ | UI-003 | High | Validate that the user can successfully save the entity with an uploaded image. |
| ☐ | UI-004 | High | Validate that the saved image remains displayed after page refresh. |
| ☐ | UI-005 | High | Validate that the saved image remains displayed after reopening the entity. |
| ☐ | UI-006 | Critical | Validate that the user can save and continue without uploading an image. |
| ☐ | UI-007 | High | Validate that the image icon appears when an image has been successfully saved. |
| ☐ | UI-008 | High | Validate that the image icon is not displayed when no image exists. |
| ☐ | UI-009 | Critical | Validate that only one image can be associated with the entity. |
| ☐ | UI-010 | High | Validate that the user cannot add a second image without replacing the existing image. |
| ☐ | UI-011 | Critical | Validate that a JPEG image just below 10 MB is accepted. |
| ☐ | UI-012 | Critical | Validate that a JPEG image of exactly 10 MB is rejected because the allowed size is less than 10 MB. |
| ☐ | UI-013 | Critical | Validate that a JPEG image larger than 10 MB is rejected. |
| ☐ | UI-014 | High | Validate that an appropriate validation message is displayed when the file exceeds the allowed size. |
| ☐ | UI-015 | Critical | Validate that unsupported file formats such as PNG, GIF, WEBP, PDF, SVG, BMP, and TIFF are rejected. |
| ☐ | UI-016 | High | Validate that an appropriate validation message is displayed for unsupported file formats. |
| ☐ | UI-017 | High | Validate that renaming an unsupported file extension to .jpeg does not bypass file validation. |
| ☐ | UI-018 | High | Validate that a corrupted JPEG image cannot be successfully uploaded. |
| ☐ | UI-019 | High | Validate that an empty/0-byte JPEG file is rejected. |
| ☐ | UI-020 | Critical | Validate that the user can replace an existing saved image with another valid JPEG image. |
| ☐ | UI-021 | High | Validate that only the newly replaced image is displayed after saving. |
| ☐ | UI-022 | High | Validate that cancelling image replacement keeps the previously saved image unchanged. |
| ☐ | UI-023 | Critical | Validate that the user can delete an existing saved image. |
| ☐ | UI-024 | High | Validate that the deleted image disappears from the UI. |
| ☐ | UI-025 | High | Validate that the image icon disappears after image deletion. |
| ☐ | UI-026 | Critical | Validate that the entity can still be saved after deleting its image. |
| ☐ | UI-027 | Medium | Validate that cancelling file selection does not change the current image state. |
| ☐ | UI-028 | Medium | Validate that a valid JPEG with a long filename can be uploaded successfully. |
| ☐ | UI-029 | Medium | Validate that supported spaces and special characters in the filename do not break the upload flow. |
| ☐ | UI-030 | High | Validate that an upload failure does not display the image as successfully saved. |
| ☐ | UI-031 | High | Validate that repeated Save actions do not create duplicate images. |
| ☐ | UI-032 | Medium | Validate that image upload, replace, and delete functionality works across supported browsers. |

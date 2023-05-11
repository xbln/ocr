# ocr
* Get sample files of Energieausweis forms on https://www.dropbox.com/sh/k6tapmszlb50qgt/AADWfTRFBQKpRyzKsyljGNGoa?dl=0.
* Sample smartphone Photos are in the .zip folders 
* The application has to make sure that photos or pdf-files with single form pages beeing uploaded or sent by email are recognized as part of one distinct Energieausweis form.
* Error messages should be visible at the UI or sent by email when the following issues occure:
  * An empty Energieausweis form has been uploaded/sent
  * A valid Energieausweis form was sent but one or more expected pages were missing (regarding only page 1 to 4)
  * More then 50% of the fields to be recognized are unreadable
  * The form could not be recognized as Energieausweis form
  * A wrong filetype (e.g. docx, xlsx, txt, gif, ...) was uploaded/attached to email
  * Sent email has no attachment
* See following sample Energieausweis form where all relevant fields that should be identified by OCR are marked red. Field names are freely selectable. Please take this only as example and be aware that Energieausweis forms may differ. 

![2 Schulstr  6, Lengef 1](https://github.com/xbln/ocr/assets/27554937/dc481443-fc2e-4465-957f-a56076efea12)
![2 Schulstr  6, Lengef 2](https://github.com/xbln/ocr/assets/27554937/a46c89ef-60e9-4866-bffe-48693a7138ce)
![2 Schulstr  6, Lengef 3](https://github.com/xbln/ocr/assets/27554937/6687639e-4dc9-4e78-b099-aa9c2f61e71f)
![2 Schulstr  6, Lengef 4](https://github.com/xbln/ocr/assets/27554937/bba8479a-9b0d-4af8-8b98-973f351863f8)

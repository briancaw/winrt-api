---
-api-id: M:Windows.Media.SpeechRecognition.SpeechContinuousRecognitionSession.Resume
-api-type: winrt method
---

<!-- Method syntax
public void Resume()
-->

# Windows.Media.SpeechRecognition.SpeechContinuousRecognitionSession.Resume

## -description
Resumes a continuous speech recognition session, if paused.

## -remarks
An error is returned if [SpeechRecognizerState](speechrecognizerstate.md) is not [Paused](speechrecognizerstate.md).

If a [SpeechRecognitionTopicConstraint](speechrecognitiontopicconstraint.md) is added after [PauseAsync](speechcontinuousrecognitionsession_pauseasync_576113822.md), [Resume](speechcontinuousrecognitionsession_resume_406343050.md) fails with error code COR_E_INVALIDOPERATION.

## -examples

## -see-also
[Speech interactions](https://msdn.microsoft.com/library/646db3ce-fa81-4727-8c21-936c81079439), [Speech design guidelines](https://msdn.microsoft.com/library/4a63a8c4-4182-4e36-ba12-4c343a56fca9), [Speech recognition and speech synthesis sample](https://go.microsoft.com/fwlink/p/?LinkID=619897)

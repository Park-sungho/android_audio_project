# android_audio_project

1. Added the Google's Audio Source of framework.
2. Added the setOemAudioPolicy() interface using JNI, Binder in frameworks.
3. Apps ues the setOemAudioPolicy() method to set the oem audio output.</tr>
   1) How to use the OEM Audio Setting.</tr>
     AudioManager audioManager = (AudioManager)getSystemService(Context.AUDIO_SERVICE);</tr>
     // This method changes Audio output to Speaker and SUBMIX </tr>
     audioManager.setOemAudioPolicy(AudioSystem.AUDIO_OEM_POLICY_SESSION_SUBMIX);</tr>

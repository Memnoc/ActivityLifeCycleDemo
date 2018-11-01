# ActivityLifeCycleDemo

Sum up of the activity LifeCycle flow:

## When the activity loads for the first time:
onCreate();
onStart();
onResume();

## When you press the home button on your phone
onPause();
onStop();

## When you resume the activity from the multi=tasking
onRestart();
onStart();
onResume();

## When you open a covering activity
onPause();
onCreate();
onStart();
onResume();
onStop();

## When you open a transparent activity
onPause();
onCreate();
onStart();
onResume();

## When you press the back button
onPause();
onResume();
onStop();
onDestroy();



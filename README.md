![Sox Commands](/sox.png)

## Sox Essential Commands

<br>

1. Convert audio format:

```
sox input.wav output.mp3
```

<br>

2. Adjust audio volume:

```
sox input.wav output.wav vol 0.8
```

<br>

3. Concatenate multiple audio files:

```
sox input1.wav input2.wav output.wav
```

<br>

4. Trim audio file:

```
sox input.wav output.wav trim 0 10
```

<br>

5. Change audio speed:

```
sox input.wav output.wav speed 1.5
```

6. Apply fade-in and fade-out effects:

```
sox input.wav output.wav fade t 0 10 1
```

<br>

7. Extract a specific channel from a stereo audio file:

```
sox input.wav output.wav remix 1
```

<br>

8. Reverse audio playback:

```
sox input.wav output.wav reverse
```

<br>

9. Apply echo effect:

```
sox input.wav output.wav echo 0.8 0.9 60 0.5
```

<br>

10. Generate a sine wave tone:

```
sox -n output.wav synth 3 sine 1000
```

<br>

11. Apply high-pass filter:

```
sox input.wav output.wav highpass 1000
```

<br>

12. Apply low-pass filter:

```
sox input.wav output.wav lowpass 8000
```

<br>

13. Mix two audio files:

```
sox -m input1.wav input2.wav output.wav
```

<br>

14. Remove silence from audio file:

```
sox input.wav output.wav silence 1 0.1 1% reverse silence 1 0.1 1% reverse
```

<br>

15. Apply reverb effect:

```
sox input.wav output.wav reverb 50 50 100 100 0.5
```

<br>

16. Change audio pitch:

```
sox input.wav output.wav pitch 600
```

<br>

17. Extract audio from a specific time range:

```
sox input.wav output.wav trim 10 20
```

<br>

18. Apply flanger effect:

```
sox input.wav output.wav flanger
```

<br>

19. Normalize audio levels:

```
sox input.wav output.wav norm
```

<br>

20. Apply chorus effect:

```
sox input.wav output.wav chorus 0.7 0.9 55 0.4 0.25 2 -t
```


<br><br>

### Developer

Shamim Hossain<br>
sparrowmtm@gmail.com<br>
+880 1758900389<br>
[https://sparrowtech.org](https://sparrowtech.org)<br>
[Upwork Profile](https://upwork.com/freelancers/~019f659b0849b9115b)
# PWM-Generator
PWM (Pulse Width Modulation) signal generator implemented in Verilog. It produces a 10 MHz PWM signal with a duty cycle that can be increased or decreased in 10% steps using two push buttons.

I designed a Verilog-based Pulse Width Modulator that generates a 10 MHz PWM signal with duty cycle control via push buttons. The design includes a custom debounce mechanism, slow clock division, and a comparator-based counter that sets the output width. A testbench simulates button presses to verify logic, while waveform outputs validate timing. The project mimics real-world embedded control systems used in motor drivers, LED dimmers, and signal modulation.

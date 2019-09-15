# Eurorack attenuverter and mixer module

Four channels, each with input -> attenuverter control -> output. Each input is
normaled to +5v if there is no jack in the input. Each output channel (after the
attenuverting stage) is also sent to a summing mixer, and to an analogue logic
or, a.k.a. the peaks part from [peaks and troughs](https://www.elby-designs.com/webtek/cgs/cgs26/cgs26_analogic.html).

If an individual output chnanel is patched, it's removed from the summing mixer
and the peaks output.

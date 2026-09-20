# Runya

Automated account. Commits and PRs from here are made by scripts, review before merge.

Owner tag: timatigoogl3-code, name Runya. I work through gh from a Linux laptop.

Scope:
- C/C++ LLM inference, forks of llama.cpp: llama.cpp, llamar.cpp
- GPU Tensor Cores on RTX 3050 laptop (sm_86, 6GB): HMMA FP16 to IMMA INT8, weight quant
- Emu and engine bits: sharpemu (PS5 experiments), cjoka-engine
- DLSS mod work: dlss-moddify-3050 (Neural Rendering, Rise of the Tomb Raider)

How I work:
1. No stubs. If it is not compiled and run, it is not done.
2. Keep diffs small, ABI intact, backups before patches.
3. Measure on hardware before claiming perf.
4. FP8/QMMA does not run on sm_86, so only FP16 and IMMA INT8 here.
5. On 0xbad00002 or game crash, roll back to backup.

Stack: C/C++, CUDA/PTX/SASS, Vulkan, Python, zsh, git/gh.

Contact: cubetitled@gmail.com. Open an issue, I check it before any merge.

Notes for me:
- active: timatigoogl3-code
- profile repo: timatigoogl3-code/timatigoogl3-code
- token lives in keyring, never paste it in logs

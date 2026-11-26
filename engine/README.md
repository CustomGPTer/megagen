# Game engines used by MegaGen (unmodified)

- `genesis-plus-gx/` — https://github.com/libretro/Genesis-Plus-GX at 51348f65738b0c75f4b8b4488fbc67645e3769af.
  Built with Android NDK r30 (30.0.16248370): `ndk-build -C libretro/jni NDK_PROJECT_PATH=. APP_BUILD_SCRIPT=Android.mk NDK_APPLICATION_MK=Application.mk APP_ABI=arm64-v8a APP_PLATFORM=android-29`
  Output `libretro.so` ships as `libgpgx.so`.
- `picodrive/` — https://github.com/libretro/picodrive at 1890c2932234c9d30f4cd3851d02228baae8f09e (with platform/libpicofe at 9ed5822606dd7ff20a782a882e8fd611cb53ba88).
  Built with: `cd jni && ndk-build NDK_PROJECT_PATH=.. APP_BUILD_SCRIPT=Android.mk NDK_APPLICATION_MK=Application.mk APP_ABI=arm64-v8a APP_PLATFORM=android-29`
  Output `libretro.so` ships as `libpicodrive.so`.

Neither engine's source was changed. Both are free for non-commercial use only; see each folder's licence.

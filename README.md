# Log

[ 38% 13068/33925] build /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/sepolicy
FAILED: /bin/bash -c "(/home/medved9112/lose/out/host/linux-x86/bin/checkpolicy -M -c 29 -o /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/sepolicy.tmp /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/policy.conf ) && (/home/medved9112/lose/out/host/linux-x86/bin/checkpolicy -M -c 29 -o /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates//sepolicy.dontaudit /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/policy.conf.dontaudit ) && (/home/medved9112/lose/out/host/linux-x86/bin/sepolicy-analyze /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/sepolicy.tmp permissive > /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/sepolicy.permissivedomains ) && (if [ \"userdebug\" = \"user\" -a -s /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/sepolicy.permissivedomains ]; then 		echo \"==========\" 1>&2; 		echo \"ERROR: permissive domains not allowed in user builds\" 1>&2; 		echo \"List of invalid domains:\" 1>&2; 		cat /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/sepolicy.permissivedomains 1>&2; 		exit 1; 		fi ) && (mv /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/sepolicy.tmp /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/sepolicy )"
libsepol.avtab_write_item: policy version 29 does not support ioctl extendedpermissions rules and one was specified
/home/medved9112/lose/out/host/linux-x86/bin/checkpolicy:  error writing /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/sepolicy.tmp
/home/medved9112/lose/out/host/linux-x86/bin/checkpolicy:  loading policy configuration from /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/policy.conf
/home/medved9112/lose/out/host/linux-x86/bin/checkpolicy:  policy configuration loaded
/home/medved9112/lose/out/host/linux-x86/bin/checkpolicy:  writing binary representation (version 29) to /home/medved9112/lose/out/target/product/smart_surf2_4g/obj/ETC/sepolicy_intermediates/sepolicy.tmp
[ 38% 13068/33925] Copy: /home/medved9112/lose/out/target/product/smart_surf2_4g/root/fstab.ranchu
ninja: build stopped: subcommand failed.
build/core/ninja.mk:151: ошибка выполнения рецепта для цели «ninja_wrapper»
make: *** [ninja_wrapper] Ошибка 1
make: выход из каталога «/home/medved9112/lose»


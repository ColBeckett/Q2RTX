cmake_minimum_required (VERSION 3.8)

SET(SRC_BASEQ2
	baseq2/g_ai.c
	baseq2/g_chase.c
	baseq2/g_cmds.c
	baseq2/g_combat.c
	baseq2/g_func.c
	baseq2/g_items.c
	baseq2/g_main.c
	baseq2/g_misc.c
	baseq2/g_monster.c
	baseq2/g_phys.c
	baseq2/g_ptrs.c
	baseq2/g_save.c
	baseq2/g_spawn.c
	baseq2/g_svcmds.c
	baseq2/g_target.c
	baseq2/g_trigger.c
	baseq2/g_turret.c
	baseq2/g_utils.c
	baseq2/g_weapon.c
	baseq2/m_actor.c
	baseq2/m_berserk.c
	baseq2/m_boss2.c
	baseq2/m_boss3.c
	baseq2/m_boss31.c
	baseq2/m_boss32.c
	baseq2/m_brain.c
	baseq2/m_chick.c
	baseq2/m_flipper.c
	baseq2/m_float.c
	baseq2/m_flyer.c
	baseq2/m_gladiator.c
	baseq2/m_gunner.c
	baseq2/m_hover.c
	baseq2/m_infantry.c
	baseq2/m_insane.c
	baseq2/m_medic.c
	baseq2/m_move.c
	baseq2/m_mutant.c
	baseq2/m_parasite.c
	baseq2/m_soldier.c
	baseq2/m_supertank.c
	baseq2/m_tank.c
	baseq2/p_client.c
	baseq2/p_hud.c
	baseq2/p_trail.c
	baseq2/p_view.c
	baseq2/p_weapon.c
)

SET(HEADERS_BASEQ2
	baseq2/g_local.h
	baseq2/g_ptrs.h
	baseq2/m_actor.h
	baseq2/m_berserk.h
	baseq2/m_boss2.h
	baseq2/m_boss31.h
	baseq2/m_boss32.h
	baseq2/m_brain.h
	baseq2/m_chick.h
	baseq2/m_flipper.h
	baseq2/m_float.h
	baseq2/m_flyer.h
	baseq2/m_gladiator.h
	baseq2/m_gunner.h
	baseq2/m_hover.h
	baseq2/m_infantry.h
	baseq2/m_insane.h
	baseq2/m_medic.h
	baseq2/m_mutant.h
	baseq2/m_parasite.h
	baseq2/m_player.h
	baseq2/m_rider.h
	baseq2/m_soldier.h
	baseq2/m_supertank.h
	baseq2/m_tank.h
)

SET(SRC_XATRIX
	xatrix/g_ai.c
	xatrix/g_chase.c
	xatrix/g_cmds.c
	xatrix/g_combat.c
	xatrix/g_func.c
	xatrix/g_items.c
	xatrix/g_main.c
	xatrix/g_misc.c
	xatrix/g_monster.c
	xatrix/g_phys.c
	xatrix/g_spawn.c
	xatrix/g_svcmds.c
	xatrix/g_target.c
	xatrix/g_trigger.c
	xatrix/g_turret.c
	xatrix/g_utils.c
	xatrix/g_weapon.c
	xatrix/monster/berserker/berserker.c
	xatrix/monster/boss2/boss2.c
	xatrix/monster/boss3/boss3.c
	xatrix/monster/boss3/boss31.c
	xatrix/monster/boss3/boss32.c
	xatrix/monster/boss5/boss5.c
	xatrix/monster/brain/brain.c
	xatrix/monster/chick/chick.c
	xatrix/monster/fixbot/fixbot.c
	xatrix/monster/flipper/flipper.c
	xatrix/monster/float/float.c
	xatrix/monster/flyer/flyer.c
	xatrix/monster/gekk/gekk.c
	xatrix/monster/gladiator/gladb.c
	xatrix/monster/gladiator/gladiator.c
	xatrix/monster/gunner/gunner.c
	xatrix/monster/hover/hover.c
	xatrix/monster/infantry/infantry.c
	xatrix/monster/insane/insane.c
	xatrix/monster/medic/medic.c
	xatrix/monster/misc/move.c
	xatrix/monster/mutant/mutant.c
	xatrix/monster/parasite/parasite.c
	xatrix/monster/soldier/soldier.c
	xatrix/monster/supertank/supertank.c
	xatrix/monster/tank/tank.c
	xatrix/player/client.c
	xatrix/player/hud.c
	xatrix/player/trail.c
	xatrix/player/view.c
	xatrix/player/weapon.c
	xatrix/savegame/savegame.c
	xatrix/shared/flash.c
	xatrix/shared/rand.c
	xatrix/shared/shared.c
)

SET(HEADERS_XATRIX
	xatrix/header/game.h
	xatrix/header/local.h
	xatrix/header/shared.h
	xatrix/monster/berserker/berserker.h
	xatrix/monster/boss2/boss2.h
	xatrix/monster/boss3/boss31.h
	xatrix/monster/boss3/boss32.h
	xatrix/monster/brain/brain.h
	xatrix/monster/chick/chick.h
	xatrix/monster/fixbot/fixbot.h
	xatrix/monster/flipper/flipper.h
	xatrix/monster/float/float.h
	xatrix/monster/flyer/flyer.h
	xatrix/monster/gekk/gekk.h
	xatrix/monster/gladiator/gladiator.h
	xatrix/monster/gunner/gunner.h
	xatrix/monster/hover/hover.h
	xatrix/monster/infantry/infantry.h
	xatrix/monster/insane/insane.h
	xatrix/monster/medic/medic.h
	xatrix/monster/misc/player.h
	xatrix/monster/mutant/mutant.h
	xatrix/monster/parasite/parasite.h
	xatrix/monster/soldier/soldier.h
	xatrix/monster/soldier/soldierh.h
	xatrix/monster/supertank/supertank.h
	xatrix/monster/tank/tank.h
	xatrix/savegame/tables/clientfields.h
	xatrix/savegame/tables/fields.h
	xatrix/savegame/tables/gamefunc_decs.h
	xatrix/savegame/tables/gamefunc_list.h
	xatrix/savegame/tables/gamemmove_decs.h
	xatrix/savegame/tables/gamemmove_list.h
	xatrix/savegame/tables/levelfields.h
)

SET(SRC_ROGUE
	rogue/g_ai.c
	rogue/g_chase.c
	rogue/g_cmds.c
	rogue/g_combat.c
	rogue/g_func.c
	rogue/g_items.c
	rogue/g_main.c
	rogue/g_misc.c
	rogue/g_monster.c
	rogue/g_newai.c
	rogue/g_newdm.c
	rogue/g_newfnc.c
	rogue/g_newtarg.c
	rogue/g_newtrig.c
	rogue/g_newweap.c
	rogue/g_phys.c
	rogue/g_spawn.c
	rogue/g_sphere.c
	rogue/g_svcmds.c
	rogue/g_target.c
	rogue/g_trigger.c
	rogue/g_turret.c
	rogue/g_utils.c
	rogue/g_weapon.c
	rogue/dm/ball.c
	rogue/dm/tag.c
	rogue/monster/berserker/berserker.c
	rogue/monster/boss2/boss2.c
	rogue/monster/boss3/boss3.c
	rogue/monster/boss3/boss31.c
	rogue/monster/boss3/boss32.c
	rogue/monster/brain/brain.c
	rogue/monster/carrier/carrier.c
	rogue/monster/chick/chick.c
	rogue/monster/flipper/flipper.c
	rogue/monster/float/float.c
	rogue/monster/flyer/flyer.c
	rogue/monster/gladiator/gladiator.c
	rogue/monster/gunner/gunner.c
	rogue/monster/hover/hover.c
	rogue/monster/infantry/infantry.c
	rogue/monster/insane/insane.c
	rogue/monster/medic/medic.c
	rogue/monster/misc/move.c
	rogue/monster/mutant/mutant.c
	rogue/monster/parasite/parasite.c
	rogue/monster/soldier/soldier.c
	rogue/monster/stalker/stalker.c
	rogue/monster/supertank/supertank.c
	rogue/monster/tank/tank.c
	rogue/monster/turret/turret.c
	rogue/monster/widow/widow.c
	rogue/monster/widow/widow2.c
	rogue/player/client.c
	rogue/player/hud.c
	rogue/player/trail.c
	rogue/player/view.c
	rogue/player/weapon.c
	rogue/savegame/savegame.c
	rogue/shared/flash.c
	rogue/shared/rand.c
	rogue/shared/shared.c
)

SET(HEADERS_ROGUE
	rogue/header/game.h
	rogue/header/local.h
	rogue/header/shared.h
	rogue/monster/berserker/berserker.h
	rogue/monster/boss2/boss2.h
	rogue/monster/boss3/boss31.h
	rogue/monster/boss3/boss32.h
	rogue/monster/brain/brain.h
	rogue/monster/carrier/carrier.h
	rogue/monster/chick/chick.h
	rogue/monster/flipper/flipper.h
	rogue/monster/float/float.h
	rogue/monster/flyer/flyer.h
	rogue/monster/gladiator/gladiator.h
	rogue/monster/gunner/gunner.h
	rogue/monster/hover/hover.h
	rogue/monster/infantry/infantry.h
	rogue/monster/insane/insane.h
	rogue/monster/medic/medic.h
	rogue/monster/misc/player.h
	rogue/monster/mutant/mutant.h
	rogue/monster/parasite/parasite.h
	rogue/monster/soldier/soldier.h
	rogue/monster/stalker/stalker.h
	rogue/monster/supertank/supertank.h
	rogue/monster/tank/tank.h
	rogue/monster/turret/turret.h
	rogue/monster/widow/widow.h
	rogue/monster/widow/widow2.h
	rogue/savegame/tables/clientfields.h
	rogue/savegame/tables/fields.h
	rogue/savegame/tables/gamefunc_decs.h
	rogue/savegame/tables/gamefunc_list.h
	rogue/savegame/tables/gamemmove_decs.h
	rogue/savegame/tables/gamemmove_list.h
	rogue/savegame/tables/levelfields.h
)

SET(SRC_ZAERO
	zaero/g_ai.c
	zaero/g_cmds.c
	zaero/g_combat.c
	zaero/g_func.c
	zaero/g_items.c
	zaero/g_main.c
	zaero/g_misc.c
	zaero/g_monster.c
	zaero/g_phys.c
	zaero/g_spawn.c
	zaero/g_svcmds.c
	zaero/g_target.c
	zaero/g_trigger.c
	zaero/g_turret.c
	zaero/g_utils.c
	zaero/g_weapon.c
	zaero/monster/actor/actor.c
	zaero/monster/berserker/berserker.c
	zaero/monster/boss/boss.c
	zaero/monster/boss2/boss2.c
	zaero/monster/boss3/boss3.c
	zaero/monster/boss3/boss31.c
	zaero/monster/boss3/boss32.c
	zaero/monster/brain/brain.c
	zaero/monster/chick/chick.c
	zaero/monster/flipper/flipper.c
	zaero/monster/float/float.c
	zaero/monster/flyer/flyer.c
	zaero/monster/gladiator/gladiator.c
	zaero/monster/gunner/gunner.c
	zaero/monster/handler/handler.c
	zaero/monster/hound/hound.c
	zaero/monster/hover/hover.c
	zaero/monster/infantry/infantry.c
	zaero/monster/insane/insane.c
	zaero/monster/medic/medic.c
	zaero/monster/misc/move.c
	zaero/monster/mutant/mutant.c
	zaero/monster/parasite/parasite.c
	zaero/monster/sentien/sentien.c
	zaero/monster/soldier/soldier.c
	zaero/monster/supertank/supertank.c
	zaero/monster/tank/tank.c
	zaero/player/client.c
	zaero/player/hud.c
	zaero/player/trail.c
	zaero/player/view.c
	zaero/player/weapon.c
	zaero/savegame/savegame.c
	zaero/shared/flash.c
	zaero/shared/shared.c
	zaero/zaero/acannon.c
	zaero/zaero/ai.c
	zaero/zaero/anim.c
	zaero/zaero/camera.c
	zaero/zaero/frames.c
	zaero/zaero/item.c
	zaero/zaero/mtest.c
	zaero/zaero/spawn.c
	zaero/zaero/trigger.c
	zaero/zaero/weapon.c
)

SET(HEADERS_ZAERO
	zaero/header/anim.h
	zaero/header/frames.h
	zaero/header/game.h
	zaero/header/local.h
	zaero/header/shared.h
	zaero/monster/actor/actor.h
	zaero/monster/berserker/berserker.h
	zaero/monster/boss/boss.h
	zaero/monster/boss2/boss2.h
	zaero/monster/boss3/boss31.h
	zaero/monster/boss3/boss32.h
	zaero/monster/brain/brain.h
	zaero/monster/chick/chick.h
	zaero/monster/flipper/flipper.h
	zaero/monster/float/float.h
	zaero/monster/flyer/flyer.h
	zaero/monster/gladiator/gladiator.h
	zaero/monster/gunner/gunner.h
	zaero/monster/handler/handler.h
	zaero/monster/hound/hound.h
	zaero/monster/hover/hover.h
	zaero/monster/infantry/infantry.h
	zaero/monster/insane/insane.h
	zaero/monster/medic/medic.h
	zaero/monster/misc/player.h
	zaero/monster/mutant/mutant.h
	zaero/monster/parasite/parasite.h
	zaero/monster/sentien/sentien.h
	zaero/monster/soldier/soldier.h
	zaero/monster/supertank/supertank.h
	zaero/savegame/tables/clientfields.h
	zaero/savegame/tables/fields.h
	zaero/savegame/tables/gamefunc_decs.h
	zaero/savegame/tables/gamefunc_list.h
	zaero/savegame/tables/gamemmove_decs.h
	zaero/savegame/tables/gamemmove_list.h
	zaero/savegame/tables/levelfields.h
)

SET(SRC_ACTION
	action/acesrc/acebot_ai.c
	action/acesrc/acebot_cmds.c
	action/acesrc/acebot_compress.c
	action/acesrc/acebot_items.c
	action/acesrc/acebot_movement.c
	action/acesrc/acebot_nodes.c
	action/acesrc/acebot_spawn.c
	action/acesrc/botchat.c
	action/acesrc/botnav.c
	action/acesrc/botscan.c
	action/acesrc/cgf_sfx_fog.c
	action/acesrc/fogstub.c
	action/a_cmds.c
	action/a_doorkick.c
	action/a_game.c
	action/a_items.c
	action/a_menu.c
	action/a_radio.c
	action/a_team.c
	action/cgf_sfx_glass.c
	action/g_ai.c
	action/g_chase.c
	action/g_cmds.c
	action/g_combat.c
	action/g_func.c
	action/g_items.c
	action/g_main.c
	action/g_misc.c
	action/g_monster.c
	action/g_phys.c
	action/g_save.c
	action/g_spawn.c
	action/g_svcmds.c
	action/g_target.c
	action/g_trigger.c
	action/g_turret.c
	action/g_utils.c
	action/g_weapon.c
	action/m_flash.c
	action/m_move.c
	action/m_tank.c
	action/p_client.c
	action/p_hud.c
	action/p_trail.c
	action/p_view.c
	action/p_weapon.c
	action/q_shared.c
)

SET(HEADERS_ACTION
	action/acesrc/acebot.h
	action/acesrc/botchat.h
	action/acesrc/botnav.h
	action/acesrc/botscan.h
	action/acesrc/cgf_sfx_fog.h
	action/a_game.h
	action/a_menu.h
	action/a_radio.h
	action/a_team.h
	action/acebot.h
	action/botnav.h
	action/cgf_sfx_glass.h
	action/g_local.h
	action/game.h
	action/m_player.h
	action/q_shared.h
)

SET(SRC_SMD
	smd/g_ai.c
	smd/g_camera.c
	smd/g_chase.c
	smd/g_cmds.c
	smd/g_combat.c
	smd/g_crane.c
	smd/g_fog.c
	smd/g_func.c
	smd/g_items.c
	smd/g_jetpack.c
	smd/g_lights.c
	smd/g_lock.c
	smd/g_main.c
	smd/g_misc.c
	smd/g_model.c
	smd/g_monster.c
	smd/g_mtrain.c
	smd/g_monster.c
	smd/g_newai.c
	smd/g_patchplayermodels.c
	smd/g_pendulum.c
	smd/g_phys.c
	smd/g_reflect.c
	smd/g_save.c
	smd/g_sound.c
	smd/g_spawn.c
	smd/g_splinetrain.c
	smd/g_svcmds.c
	smd/g_target.c
	smd/g_thing.c
	smd/g_tracktrain.c
	smd/g_trigger.c
	smd/g_turret.c
	smd/g_utils.c
	smd/g_vehicle.c
	smd/g_weapon.c
	smd/g_wes.c
	smd/m_actor.c
	smd/m_actor_weap.c
	smd/m_berserk.c
	smd/m_boss2.c
	smd/m_boss3.c
	smd/m_boss31.c
	smd/m_boss32.c
	smd/m_brain.c
	smd/m_chick.c
	smd/m_flash.c
	smd/m_flipper.c
	smd/m_float.c
	smd/m_flyer.c
	smd/m_gladiator.c
	smd/m_gunner.c
	smd/m_hover.c
	smd/m_infantry.c
	smd/m_insane.c
	smd/m_medic.c
	smd/m_move.c
	smd/m_mutant.c
	smd/m_parasite.c
	smd/m_sentrybot.c
	smd/m_soldier.c
	smd/m_supertank.c
	smd/m_tank.c
	smd/majbitch.c
	smd/p_chase.c
	smd/p_client.c
	smd/p_hud.c
	smd/p_menu.c
	smd/p_text.c
	smd/p_trail.c
	smd/p_view.c
	smd/p_weapon.c
	smd/q_shared.c
)

SET(HEADERS_SMD
	smd/fmod.h
	smd/g_func_decs.h
	smd/g_func_list.h
	smd/g_local.h
	smd/g_mmove_decs.h
	smd/g_mmove_list.h
	smd/m_actor.h
	smd/m_berserk.h
	smd/m_boss2.h
	smd/m_boss31.h
	smd/m_boss32.h
	smd/m_brain.h
	smd/m_chick.h
	smd/m_flipper.h
	smd/m_float.h
	smd/m_flyer.h
	smd/m_gladiator.h
	smd/m_gunner.h
	smd/m_hover.h
	smd/m_infantry.h
	smd/m_insane.h
	smd/m_medic.h
	smd/m_mutant.h
	smd/m_parasite.h
	smd/m_player.h
	smd/m_rider.h
	smd/m_soldier.h
	smd/m_supertank.h
	smd/m_tank.h
	smd/p_menu.h
	smd/p_text.h
	smd/pak.h
	smd/q_shared.h
	smd/resource.h
)



SET(SRC_CLIENT
	client/ascii.c
	client/console.c
	client/crc.c
	client/demo.c
	client/download.c
	client/effects.c
	client/entities.c
	client/gtv.c
	client/input.c
	client/keys.c
	client/locs.c
	client/main.c
	client/newfx.c
#	client/null.c
	client/parse.c
	client/precache.c
	client/predict.c
	client/refresh.c
	client/screen.c
	client/tent.c
	client/view.c
	client/ui/demos.c
	client/ui/menu.c
	client/ui/playerconfig.c
	client/ui/playermodels.c
	client/ui/script.c
	client/ui/servers.c
	client/ui/ui.c
	client/sound/dma.c
	client/sound/al.c
	client/sound/main.c
	client/sound/mem.c
	client/sound/mix.c
	client/sound/ogg.c
#	client/sound/qal/fixed.c
	client/sound/qal/dynamic.c
)

SET(SRC_CLIENT_HTTP
	client/http.c
)

SET(HEADERS_CLIENT
	client/client.h
	client/ui/ui.h
	client/sound/sound.h
	client/sound/qal/dynamic.h
	client/sound/qal/fixed.h
)

SET(SRC_SERVER
	server/commands.c
	server/entities.c
	server/game.c
	server/init.c
	server/main.c
	server/mvd.c
	server/send.c
	server/user.c
	server/world.c
	server/mvd/client.c
	server/mvd/parse.c
	server/mvd/game.c
	server/save.c
)

SET(HEADERS_SERVER
	server/server.h
)

SET(SRC_COMMON
	common/bsp.c
	common/cmd.c
	common/cmodel.c
	common/common.c
	common/cvar.c
	common/error.c
	common/field.c
	common/fifo.c
	common/files.c
	common/math.c
	common/mdfour.c
	common/msg.c
	common/pmove.c
	common/prompt.c
	common/sizebuf.c
#	common/tests.c
	common/utils.c
	common/zone.c
	common/net/chan.c
	common/net/net.c
	common/x86/fpu.c
)

SET(HEADERS_COMMON
	common/net/inet_ntop.h
	common/net/inet_pton.h
	common/net/win.h
)

SET(SRC_REFRESH
	refresh/images.c
	refresh/models.c
	refresh/stb/stb.c
)


SET(SRC_GL
	refresh/gl/draw.c
	refresh/gl/hq2x.c
	refresh/gl/images.c
	refresh/gl/main.c
	refresh/gl/mesh.c
	refresh/gl/models.c
	refresh/gl/sky.c
	refresh/gl/state.c
	refresh/gl/surf.c
	refresh/gl/tess.c
	refresh/gl/world.c
	refresh/gl/qgl/dynamic.c
#	refresh/gl/qgl/fixed.c
)

SET(HEADERS_GL
	refresh/gl/arbfp.h
	refresh/gl/gl.h
)

SET(SRC_SHARED
	shared/m_flash.c
	shared/shared.c
)

SET(SRC_LINUX
	unix/hunk.c
	unix/system.c
	unix/tty.c
)

SET(SRC_LINUX_CLIENT
	unix/sdl2/sound.c
	unix/sdl2/video.c
)

SET(SRC_WINDOWS
	windows/ac.c
	windows/debug.c
	windows/hunk.c
	windows/system.c
)

SET(SRC_WINDOWS_CLIENT
	windows/wave.c
	unix/sdl2/video.c
)

	#windows/ascii.c
	#windows/client.c
	#windows/dinput.c
	#windows/dsound.c
	#windows/glimp.c
	#windows/swimp.c
	#windows/wgl.c
	#unix/sdl2/sound.c

SET(HEADERS_WINDOWS
	windows/wgl.h
	windows/glimp.h
	windows/client.h
	windows/threads/threads.h
)

SET(SRC_VKPT
	refresh/vkpt/asvgf.c
	refresh/vkpt/bloom.c
	refresh/vkpt/bsp_mesh.c
	refresh/vkpt/draw.c
	refresh/vkpt/main.c
	refresh/vkpt/material.c
	refresh/vkpt/matrix.c
	refresh/vkpt/mgpu.c
	refresh/vkpt/models.c
	refresh/vkpt/path_tracer.c
	refresh/vkpt/physical_sky.c
	refresh/vkpt/precomputed_sky.c
	refresh/vkpt/profiler.c
	refresh/vkpt/shadow_map.c
	refresh/vkpt/textures.c
	refresh/vkpt/tone_mapping.c
	refresh/vkpt/transparency.c
	refresh/vkpt/uniform_buffer.c
	refresh/vkpt/vertex_buffer.c
	refresh/vkpt/vk_util.c
	refresh/vkpt/buddy_allocator.c
	refresh/vkpt/device_memory_allocator.c
	refresh/vkpt/god_rays.c
)

SET(HEADERS_VKPT
	refresh/vkpt/vkpt.h
	refresh/vkpt/vk_util.h
	refresh/vkpt/buddy_allocator.h
	refresh/vkpt/device_memory_allocator.h
	refresh/vkpt/material.h
	refresh/vkpt/physical_sky.h
	refresh/vkpt/precomputed_sky.h
)

set(SRC_SHADERS
	refresh/vkpt/shader/animate_materials.comp
	refresh/vkpt/shader/god_rays_filter.comp
	refresh/vkpt/shader/god_rays.comp
	refresh/vkpt/shader/bloom_composite.comp
	refresh/vkpt/shader/bloom_blur.comp
	refresh/vkpt/shader/primary_rays.rgen
	refresh/vkpt/shader/direct_lighting.rgen
	refresh/vkpt/shader/checkerboard_interleave.comp
	refresh/vkpt/shader/indirect_lighting.rgen
	refresh/vkpt/shader/path_tracer.rchit
	refresh/vkpt/shader/path_tracer.rmiss
	refresh/vkpt/shader/path_tracer_particle.rahit
	refresh/vkpt/shader/path_tracer_sprite.rahit
	refresh/vkpt/shader/path_tracer_beam.rahit
	refresh/vkpt/shader/path_tracer_explosion.rahit
	refresh/vkpt/shader/path_tracer_shadow.rmiss
	refresh/vkpt/shader/asvgf_atrous.comp
	refresh/vkpt/shader/asvgf_fwd_project.comp
	refresh/vkpt/shader/asvgf_gradient_atrous.comp
	refresh/vkpt/shader/asvgf_gradient_img.comp
	refresh/vkpt/shader/asvgf_lf.comp
	refresh/vkpt/shader/asvgf_seed_rng.comp
	refresh/vkpt/shader/asvgf_taa.comp
	refresh/vkpt/shader/asvgf_temporal.comp
	refresh/vkpt/shader/instance_geometry.comp
	refresh/vkpt/shader/tone_mapping_histogram.comp
	refresh/vkpt/shader/tone_mapping_curve.comp
    refresh/vkpt/shader/tone_mapping_apply.comp
	refresh/vkpt/shader/physical_sky.comp
	refresh/vkpt/shader/physical_sky_space.comp
	refresh/vkpt/shader/shadow_map.vert
	refresh/vkpt/shader/sky_buffer_resolve.comp
	refresh/vkpt/shader/stretch_pic.frag
	refresh/vkpt/shader/stretch_pic.vert
	refresh/vkpt/shader/final_blit_lanczos.frag
	refresh/vkpt/shader/final_blit.vert
)

include(../cmake/compileShaders.cmake)

if (GLSLANG_COMPILER)
	foreach(s ${SRC_SHADERS})
		compile_shader(SOURCE_FILE ${s} OUTPUT_FILE_LIST shader_bytecode)
	endforeach()

	add_custom_target(shaders DEPENDS ${shader_bytecode})
else()
    message(WARNING "Could not find shader compiler: you're on your own to build the shaders")
endif()

# Embed version number
ADD_DEFINITIONS(-DVERSION_MAJOR=${Q2RTX_VERSION_MAJOR})
ADD_DEFINITIONS(-DVERSION_MINOR=${Q2RTX_VERSION_MINOR})
ADD_DEFINITIONS(-DVERSION_POINT=${Q2RTX_VERSION_POINT})
ADD_DEFINITIONS(-DVERSION_SHA=${Q2RTX_VERSION_SHA})

# Operating system
add_definitions(-DOSTYPE="${CMAKE_SYSTEM_NAME}")

# Architecture string
string(REGEX REPLACE "amd64" "x86_64" ARCH "${CMAKE_SYSTEM_PROCESSOR}")
string(REGEX REPLACE "i.86" "i386" ARCH "${ARCH}")
string(REGEX REPLACE "^arm.*" "arm" ARCH "${ARCH}")
add_definitions(-DARCH="${ARCH}")

ADD_DEFINITIONS(-DHAVE_CONFIG_H=1 -DCURL_STATICLIB)

IF(WIN32)
	ADD_DEFINITIONS(-D_CRT_SECURE_NO_WARNINGS)
ENDIF()

ADD_LIBRARY(gamex86_baseq2 SHARED ${SRC_BASEQ2} ${HEADERS_BASEQ2} ${SRC_SHARED})
ADD_LIBRARY(gamex86_xatrix SHARED ${SRC_XATRIX} ${HEADERS_XATRIX})
ADD_LIBRARY(gamex86_rogue SHARED ${SRC_ROGUE} ${HEADERS_ROGUE})
ADD_LIBRARY(gamex86_zaero SHARED ${SRC_ZAERO} ${HEADERS_ZAERO})
ADD_LIBRARY(gamex86_action SHARED ${SRC_ACTION} ${HEADERS_ACTION})
ADD_LIBRARY(gamex86_smd SHARED ${SRC_SMD} ${HEADERS_SMD})

IF(WIN32)
ADD_EXECUTABLE(client WIN32 
	${SRC_CLIENT} ${HEADERS_CLIENT} 
	${SRC_COMMON} ${HEADERS_COMMON} 
	${SRC_REFRESH} ${SRC_SHADERS} 
	${SRC_SHARED} 
	${SRC_WINDOWS} ${SRC_WINDOWS_CLIENT} ${HEADERS_WINDOWS}
	${SRC_SERVER} ${HEADERS_SERVER}
	windows/res/q2rtx.rc
)
ADD_EXECUTABLE(server 
	${SRC_COMMON} ${HEADERS_COMMON} 
	${SRC_SHARED} 
	${SRC_WINDOWS} ${HEADERS_WINDOWS}
	${SRC_SERVER} ${HEADERS_SERVER}
	server/ac.c
	client/null.c
	windows/res/q2rtxded.rc
)
ELSE()
ADD_EXECUTABLE(client
	${SRC_CLIENT} ${HEADERS_CLIENT} 
	${SRC_COMMON} ${HEADERS_COMMON} 
	${SRC_REFRESH} ${SRC_SHADERS} 
	${SRC_SHARED} 
	${SRC_LINUX} ${SRC_LINUX_CLIENT}
	${SRC_SERVER} ${HEADERS_SERVER}
)
ADD_EXECUTABLE(server
	${SRC_COMMON} ${HEADERS_COMMON} 
	${SRC_SHARED} 
	${SRC_LINUX}
	${SRC_SERVER} ${HEADERS_SERVER}
	server/ac.c
	client/null.c
)
ENDIF()

TARGET_COMPILE_DEFINITIONS(client PRIVATE USE_SERVER=1 USE_CLIENT=1)
TARGET_COMPILE_DEFINITIONS(server PRIVATE USE_SERVER=1 USE_CLIENT=0)

IF(CONFIG_USE_CURL)
	TARGET_SOURCES(client PRIVATE ${SRC_CLIENT_HTTP})
	TARGET_COMPILE_DEFINITIONS(client PRIVATE USE_CURL=1)
	TARGET_LINK_LIBRARIES(client libcurl)
ENDIF()

if (GLSLANG_COMPILER)
	add_dependencies(client shaders)
endif()

IF (CONFIG_GL_RENDERER)
	TARGET_SOURCES(client PRIVATE ${SRC_GL} ${HEADERS_GL})
	TARGET_COMPILE_DEFINITIONS(client PRIVATE REF_GL=1 USE_REF=1)
ENDIF()

IF (CONFIG_VKPT_RENDERER)
	TARGET_SOURCES(client PRIVATE ${SRC_VKPT} ${HEADERS_VKPT})
	TARGET_INCLUDE_DIRECTORIES(client PRIVATE refresh/vkpt/include)
	LINK_DIRECTORIES(client PRIVATE refresh/vkpt/include/vulkan)
	TARGET_COMPILE_DEFINITIONS(client PRIVATE REF_VKPT=1 USE_REF=1)
	IF (CONFIG_VKPT_ENABLE_DEVICE_GROUPS)
		TARGET_COMPILE_DEFINITIONS(client PRIVATE VKPT_DEVICE_GROUPS)
	ENDIF()
	if (CONFIG_VKPT_ENABLE_IMAGE_DUMPS)
		TARGET_COMPILE_DEFINITIONS(client PRIVATE VKPT_IMAGE_DUMPS)
	ENDIF()
	IF (WIN32)
	TARGET_LINK_LIBRARIES(client vulkan-1)
	ELSE ()
	TARGET_LINK_LIBRARIES(client vulkan)
	ENDIF()
ENDIF()

TARGET_LINK_LIBRARIES(client stb)

SOURCE_GROUP("baseq2\\sources" FILES ${SRC_BASEQ2})
SOURCE_GROUP("baseq2\\headers" FILES ${HEADERS_BASEQ2})
SOURCE_GROUP("xatrix\\sources" FILES ${SRC_XATRIX})
SOURCE_GROUP("xatrix\\headers" FILES ${HEADERS_XATRIX})
SOURCE_GROUP("rogue\\sources" FILES ${SRC_ROGUE})
SOURCE_GROUP("rogue\\headers" FILES ${HEADERS_ROGUE})
SOURCE_GROUP("zaero\\sources" FILES ${SRC_ZAERO})
SOURCE_GROUP("zaero\\headers" FILES ${HEADERS_ZAERO})
SOURCE_GROUP("action\\sources" FILES ${SRC_ACTION})
SOURCE_GROUP("action\\headers" FILES ${HEADERS_ACTION})
SOURCE_GROUP("smd\\sources" FILES ${SRC_SMD})
SOURCE_GROUP("smd\\headers" FILES ${HEADERS_SMD})
SOURCE_GROUP("client\\sources" FILES ${SRC_CLIENT})
SOURCE_GROUP("client\\headers" FILES ${HEADERS_CLIENT})
SOURCE_GROUP("server\\sources" FILES ${SRC_SERVER})
SOURCE_GROUP("server\\headers" FILES ${HEADERS_SERVER})
SOURCE_GROUP("common\\sources" FILES ${SRC_COMMON})
SOURCE_GROUP("common\\headers" FILES ${HEADERS_COMMON})
SOURCE_GROUP("refresh\\sources" FILES ${SRC_REFRESH} ${SRC_VKPT})
SOURCE_GROUP("refresh\\headers" FILES ${HEADERS_VKPT})
SOURCE_GROUP("refresh\\shaders" FILES ${SRC_SHADERS})
SOURCE_GROUP("shared\\sources" FILES ${SRC_SHARED})
SOURCE_GROUP("windows\\sources" FILES ${SRC_WINDOWS})
SOURCE_GROUP("windows\\headers" FILES ${HEADERS_WINDOWS})

IF (WIN32)
	TARGET_INCLUDE_DIRECTORIES(client PRIVATE ../VC/inc)
	TARGET_INCLUDE_DIRECTORIES(server PRIVATE ../VC/inc)
	TARGET_INCLUDE_DIRECTORIES(gamex86_baseq2 PRIVATE ../VC/inc)
	TARGET_INCLUDE_DIRECTORIES(gamex86_xatrix PRIVATE ../VC/inc)
	TARGET_INCLUDE_DIRECTORIES(gamex86_rogue PRIVATE ../VC/inc)
	TARGET_INCLUDE_DIRECTORIES(gamex86_zaero PRIVATE ../VC/inc)
	TARGET_INCLUDE_DIRECTORIES(gamex86_action PRIVATE ../VC/inc)
	TARGET_INCLUDE_DIRECTORIES(gamex86_smd PRIVATE ../VC/inc)
	TARGET_SOURCES(gamex86_baseq2 PRIVATE windows/res/baseq2.rc)

	TARGET_LINK_LIBRARIES(client winmm ws2_32)
	TARGET_LINK_LIBRARIES(server winmm ws2_32)

	set_target_properties(client PROPERTIES VS_DEBUGGER_WORKING_DIRECTORY "${CMAKE_SOURCE_DIR}")
	set_target_properties(server PROPERTIES VS_DEBUGGER_WORKING_DIRECTORY "${CMAKE_SOURCE_DIR}")

	# macro redefinition, deprecation
	target_compile_options(client PRIVATE /wd4005 /wd4996)
	target_compile_options(server PRIVATE /wd4005 /wd4996)
	target_compile_options(gamex86_baseq2 PRIVATE /wd4005 /wd4996)
	target_compile_options(gamex86_xatrix PRIVATE /wd4005 /wd4996)
	target_compile_options(gamex86_rogue PRIVATE /wd4005 /wd4996)
	target_compile_options(gamex86_zaero PRIVATE /wd4005 /wd4996)
	target_compile_options(gamex86_action PRIVATE /wd4005 /wd4996)
	target_compile_options(gamex86_smd PRIVATE /wd4005 /wd4996)
ENDIF()

TARGET_INCLUDE_DIRECTORIES(gamex86_baseq2 PRIVATE ../inc)
TARGET_INCLUDE_DIRECTORIES(gamex86_xatrix PRIVATE ../inc)
TARGET_INCLUDE_DIRECTORIES(gamex86_rogue PRIVATE ../inc)
TARGET_INCLUDE_DIRECTORIES(gamex86_zaero PRIVATE ../inc)
TARGET_INCLUDE_DIRECTORIES(gamex86_action PRIVATE ../inc)
TARGET_INCLUDE_DIRECTORIES(gamex86_smd PRIVATE ../inc)

TARGET_INCLUDE_DIRECTORIES(client PRIVATE ../inc)
TARGET_INCLUDE_DIRECTORIES(client PRIVATE "${ZLIB_INCLUDE_DIRS}")
TARGET_INCLUDE_DIRECTORIES(server PRIVATE ../inc)
TARGET_INCLUDE_DIRECTORIES(server PRIVATE "${ZLIB_INCLUDE_DIRS}")

# Use dynamic zlib for steam runtime
if (CONFIG_LINUX_STEAM_RUNTIME_SUPPORT)
    TARGET_LINK_LIBRARIES(client SDL2main SDL2-static z)
    TARGET_LINK_LIBRARIES(server SDL2main SDL2-static z)
else()
    TARGET_LINK_LIBRARIES(client SDL2main SDL2-static zlibstatic)
    TARGET_LINK_LIBRARIES(server SDL2main SDL2-static zlibstatic)
endif()

SET_TARGET_PROPERTIES(client
    PROPERTIES
    OUTPUT_NAME "q2rtxgame"
    RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}"
    RUNTIME_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}"
    RUNTIME_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}"
    RUNTIME_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}"
    RUNTIME_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}"
    DEBUG_POSTFIX ""
)

SET_TARGET_PROPERTIES(server
    PROPERTIES
    OUTPUT_NAME "q2rtxded"
    RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}"
    RUNTIME_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}"
    RUNTIME_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}"
    RUNTIME_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}"
    RUNTIME_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}"
    DEBUG_POSTFIX ""
)

# specify both LIBRARY and RUNTIME because one works only on Windows and another works only on Linux

SET_TARGET_PROPERTIES(gamex86_baseq2
    PROPERTIES
    LIBRARY_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/baseq2"
    LIBRARY_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/baseq2"
    LIBRARY_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/baseq2"
    LIBRARY_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/baseq2"
    LIBRARY_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/baseq2"
    RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/baseq2"
    RUNTIME_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/baseq2"
    RUNTIME_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/baseq2"
    RUNTIME_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/baseq2"
    RUNTIME_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/baseq2"
    PREFIX ""
    DEBUG_POSTFIX ""
)

SET_TARGET_PROPERTIES(gamex86_xatrix
    PROPERTIES
    LIBRARY_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/xatrix"
    LIBRARY_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/xatrix"
    LIBRARY_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/xatrix"
    LIBRARY_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/xatrix"
    LIBRARY_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/xatrix"
    RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/xatrix"
    RUNTIME_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/xatrix"
    RUNTIME_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/xatrix"
    RUNTIME_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/xatrix"
    RUNTIME_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/xatrix"
    PREFIX ""
    DEBUG_POSTFIX ""
)

SET_TARGET_PROPERTIES(gamex86_rogue
    PROPERTIES
    LIBRARY_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/rogue"
    LIBRARY_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/rogue"
    LIBRARY_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/rogue"
    LIBRARY_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/rogue"
    LIBRARY_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/rogue"
    RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/rogue"
    RUNTIME_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/rogue"
    RUNTIME_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/rogue"
    RUNTIME_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/rogue"
    RUNTIME_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/rogue"
    PREFIX ""
    DEBUG_POSTFIX ""
)

SET_TARGET_PROPERTIES(gamex86_zaero
    PROPERTIES
    LIBRARY_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/zaero"
    LIBRARY_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/zaero"
    LIBRARY_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/zaero"
    LIBRARY_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/zaero"
    LIBRARY_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/zaero"
    RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/zaero"
    RUNTIME_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/zaero"
    RUNTIME_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/zaero"
    RUNTIME_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/zaero"
    RUNTIME_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/zaero"
    PREFIX ""
    DEBUG_POSTFIX ""
)

SET_TARGET_PROPERTIES(gamex86_action
    PROPERTIES
    LIBRARY_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/action"
    LIBRARY_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/action"
    LIBRARY_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/action"
    LIBRARY_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/action"
    LIBRARY_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/action"
    RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/action"
    RUNTIME_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/action"
    RUNTIME_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/action"
    RUNTIME_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/action"
    RUNTIME_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/action"
    PREFIX ""
    DEBUG_POSTFIX ""
)

SET_TARGET_PROPERTIES(gamex86_smd
    PROPERTIES
    LIBRARY_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/smd"
    LIBRARY_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/smd"
    LIBRARY_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/smd"
    LIBRARY_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/smd"
    LIBRARY_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/smd"
    RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}/smd"
    RUNTIME_OUTPUT_DIRECTORY_DEBUG "${CMAKE_SOURCE_DIR}/smd"
    RUNTIME_OUTPUT_DIRECTORY_RELEASE "${CMAKE_SOURCE_DIR}/smd"
    RUNTIME_OUTPUT_DIRECTORY_RELWITHDEBINFO "${CMAKE_SOURCE_DIR}/smd"
    RUNTIME_OUTPUT_DIRECTORY_MINSIZEREL "${CMAKE_SOURCE_DIR}/smd"
    PREFIX ""
    DEBUG_POSTFIX ""
)

IF(IS_64_BIT)
	SET_TARGET_PROPERTIES(gamex86_baseq2
		PROPERTIES
		LIBRARY_OUTPUT_NAME "gamex86_64"
		RUNTIME_OUTPUT_NAME "gamex86_64"
	)
	
SET_TARGET_PROPERTIES(gamex86_xatrix
		PROPERTIES
		LIBRARY_OUTPUT_NAME "gamex86_64"
		RUNTIME_OUTPUT_NAME "gamex86_64"
	)	
	
SET_TARGET_PROPERTIES(gamex86_rogue
		PROPERTIES
		LIBRARY_OUTPUT_NAME "gamex86_64"
		RUNTIME_OUTPUT_NAME "gamex86_64"
	)		
	
SET_TARGET_PROPERTIES(gamex86_zaero
		PROPERTIES
		LIBRARY_OUTPUT_NAME "gamex86_64"
		RUNTIME_OUTPUT_NAME "gamex86_64"
	)		
	
SET_TARGET_PROPERTIES(gamex86_action
		PROPERTIES
		LIBRARY_OUTPUT_NAME "gamex86_64"
		RUNTIME_OUTPUT_NAME "gamex86_64"
	)			
	
SET_TARGET_PROPERTIES(gamex86_smd
		PROPERTIES
		LIBRARY_OUTPUT_NAME "gamex86_64"
		RUNTIME_OUTPUT_NAME "gamex86_64"
	)		
ENDIF()

IF(CONFIG_LINUX_PACKAGING_SUPPORT)
    # Put the real game binary in /usr/share so we can have a wrapper in /usr/bin
    INSTALL(TARGETS client DESTINATION share/quake2rtx/bin COMPONENT shareware)
    INSTALL(TARGETS server DESTINATION games COMPONENT shareware)

    # Compress NVIDIA custom content
    INSTALL(CODE "set(SOURCE \"${CMAKE_SOURCE_DIR}\")"
        SCRIPT "${CMAKE_SOURCE_DIR}/setup/package_media.cmake"
        SCRIPT "${CMAKE_SOURCE_DIR}/setup/package_shaders.cmake"
        COMPONENT shareware)
    INSTALL(TARGETS gamex86 DESTINATION share/quake2rtx/baseq2 COMPONENT shareware)

    # Package data files, including the shareware pak0 for demo levels
    set (SHAREWARE_DATA_FILES_LIST
        "${CMAKE_SOURCE_DIR}/baseq2/q2rtx_media.pkz"
        "${CMAKE_SOURCE_DIR}/baseq2/shaders.pkz"
        "${CMAKE_SOURCE_DIR}/baseq2/blue_noise.pkz"
        "${CMAKE_SOURCE_DIR}/baseq2/shareware/pak0.pak"
    )
    INSTALL(FILES
        ${SHAREWARE_DATA_FILES_LIST}
        DESTINATION share/quake2rtx/baseq2
        COMPONENT shareware)

    # Package shareware player model
    INSTALL(DIRECTORY
        "${CMAKE_SOURCE_DIR}/baseq2/shareware/players"
        DESTINATION share/quake2rtx/baseq2
        COMPONENT shareware)

    # Package the legal and info files
    INSTALL(FILES
        "${CMAKE_SOURCE_DIR}/license.txt"
        "${CMAKE_SOURCE_DIR}/notice.txt"
        "${CMAKE_SOURCE_DIR}/readme.md"
        "${CMAKE_SOURCE_DIR}/changelog.md"
        DESTINATION share/quake2rtx/
        COMPONENT shareware)

    # Package the icon/desktop file
    INSTALL(FILES
        "${CMAKE_SOURCE_DIR}/setup/q2rtx.desktop"
        DESTINATION share/applications/
        COMPONENT shareware)
    INSTALL(FILES
        "${CMAKE_SOURCE_DIR}/setup/q2rtx.png"
        DESTINATION share/pixmaps/
        COMPONENT shareware)

    # Install Client Wrapper
    INSTALL(FILES
        "${CMAKE_SOURCE_DIR}/setup/q2rtx.sh"
        DESTINATION games/
        PERMISSIONS OWNER_READ OWNER_WRITE OWNER_EXECUTE GROUP_READ GROUP_EXECUTE WORLD_READ WORLD_EXECUTE
        COMPONENT shareware
	RENAME q2rtx)

    # Install PAK file finder
    INSTALL(FILES
        "${CMAKE_SOURCE_DIR}/setup/find-retail-paks.sh"
        DESTINATION share/quake2rtx/bin
        PERMISSIONS OWNER_READ OWNER_WRITE OWNER_EXECUTE GROUP_READ GROUP_EXECUTE WORLD_READ WORLD_EXECUTE
        COMPONENT shareware)
ENDIF()

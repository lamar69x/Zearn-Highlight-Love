# Zearn-Highlight-Love
Just copy this and boom luh dawg

javascript:var tasks=Dent.utils.Store._modules.root.getChild("tasks")._rawModule;Dent.utils.Store.registerModule("tasks",tasks),Dent.utils.Store.unregisterModule("tasks"),tasks.getters.currentGradingState=(t,e)=>t=>{const r=null!=e.latestResponse(t),s=e.isEvaluated(t),o=e.isBrancher(t);if(r){if(s||o){const s=r&&e.latestResponse(t).is_correct,o=e.hasExhaustedTries(t),a=e.hasAutocorrect(t)&&!e.hasOldAutocorrect(t),c=e.hasGhostAutocorrect(t),u=e.isPreGhostAutocorrectCleared(t),l=e.isCorrectableCleared(t),i=e.isTryAgainCleared(t);return s?"correct":o?a?c&&!u?"pre-ghost-autocorrect":l?"autocorrected":"correctable":"correct":i?"":"correct"}return"correct"}return""},Dent.utils.Store.registerModule("tasks",tasks);

import { ReplrodOptimizationPlugin } from '@listenrightmeow/replrod/plugin/OptimizationPlugin';
import { CriticalCSSOptimizer } from './CriticalCSSOptimizer.js';

const plugin: ReplrodOptimizationPlugin = {
  metadata: {
    name: '@listenrightmeow/replrod-plugin-critical-css',
    version: '1.0.0',
    description: 'Critical CSS inlining optimization for replrod',
    author: '@listenrightmeow',
    expectedImprovement: '60-70% faster initial render'
  },
  optimization: new CriticalCSSOptimizer(),
  
  async onLoad() {
    console.debug('Critical CSS optimization plugin loaded');
  },
  
  async onUnload() {
    console.debug('Critical CSS optimization plugin unloaded');
  }
};

export { plugin };
export default plugin;
<template>
  <div class="game-landing">
    <div class="game-wrapper">
      <div class="game-chessboard">
        <chess-board />
      </div>
      <div class="game-movelog">
        <h2>Move log</h2>
        <move-log />
      </div>
    </div>
  </div>
</template>

<script>
import ChessBoard from './ChessBoard';
import MoveLog from './MoveLog';

export default {
  name: 'Game',
  components: {
    ChessBoard,
    MoveLog,
  },
};
</script>
